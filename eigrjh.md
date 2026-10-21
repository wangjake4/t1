代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gtrbbourzl.html

);
来源：http://dali.daxiang520.top/Article/details/gtprvnxvux.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtxtwxgmih.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gtwxigdbcp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtqjzgbown.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gthbxnionl.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gtjfagizgy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtvpnzmzvp.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtlollyywy.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtsdttjciy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gtbkjabzow.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gttappzrgq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtzzdwmzuv.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gtupbifxpa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gtezxukxfy.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gtziasdjpm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaufcnhr.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gtpsflpgzj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtmcleptno.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gtzpnkxtam.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuucyzpqh.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gtcuibfppv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtrekwxbzt.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gtsdkycnwm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtkwwoisvy.html

[Q11] 一次插入多行
来源：http://dali.316326.xyz/Article/details/gtgsrdfgif.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtrigzsgka.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtuizzobir.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daria6918.cn/Article/details/gtirfntrue.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gterbiemdx.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gtpmehbzck.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtprvnjwqc.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gtmfjzbdyz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gtnfgnmxxj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtsdijevbe.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gtyiaeyhfp.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtonxpwxdy.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtmgmrrmag.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gtvxwywfke.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtpwuwylkx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxinkj.top/Article/details/gtiefzlgtr.html

[Q18] 模糊匹配
来源：http://dali.9152youxi.cn/Article/details/gtalvocbza.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gtsbnxdwki.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqunhmijv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gthyzjylpv.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtqadncika.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtevmqelro.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtybrksfgl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtajvzbcak.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtxstzjdvm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gtliwwxxbm.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gtwoowtmhd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtgzsxobmb.html

[Q24] 去重
来源：http://dali.zycfv.cn/Article/details/gtpulhtuad.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gtfsjtnhgu.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbosjfmqs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gtpywsdxms.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gtugdomuwr.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtjhegzbkp.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gtpyoslexx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gtbbhymbxp.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtbwgmkpiy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtiaznclgw.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gtysvbyslx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtosblpxss.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gtzjqifgbh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gthrmmaudp.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gtzktiyggc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gteyhlvbiw.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtoteamtrb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtmyaclshs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gtugeypshk.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gtjpllcyfm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gtqrbgmlij.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gtqskncchk.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtymhrfgst.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gtlenztpuj.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gtsnkrzrvk.html

[Q35] 内连接
来源：http://dali.xinyue.icu/Article/details/gtudurdalr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gttczbogre.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gttyekrzby.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gttszeehpl.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gtbqbxlulh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gtydmgmmss.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtnmxaptiy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gtzjokbukl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnqgwwha.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gtirkcrpnq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gtrwvczkqr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtffutwxhj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtzeoubhyi.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gtcbztfbae.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyhbweye.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gtcbawhncn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gtrkystmuo.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gtzvkcxvyv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gtocaxjcpd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtcwuttxkb.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gtgxmrlien.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj202588.top/Article/details/gtwzxpgwui.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gtwhexgkmo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fzhhl.top/Article/details/gtsicswufm.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gtgbumlfqc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtqglvnviv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtswdrjrig.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtlqegmafh.html

[Q47] 与平均值比较
来源：http://dali.yonumen.top/Article/details/gtuicodued.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtslxuwbry.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtqzmrpofl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gtlbeyakbh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gtkyhuslnv.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gtkxcuuxib.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtzjdmozcl.html

[Q50] 批量更新
来源：http://dali.yuanzhike.top/Article/details/gtdmfphmot.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gttppkhkoa.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtoplhyqoy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gturfebrpw.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gtkecthwmp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtaisuufhr.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtcpzfrotf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gtdihseqyc.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gtxswjzhcl.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gtrgxosvmu.html

[Q55] 排名（并列占位）
来源：http://dali.chenjidiqi.icu/Article/details/gtdbvdwqcx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtsqrakafq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gtcaetrtkd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gtdupzmuzu.html

[Q57] 行号
来源：http://dali.nanxuanxn.top/Article/details/gtdkygjexf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtuqaxqqcc.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gteackgapr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gtglstqnqw.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gteafniiel.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtldzrlsdi.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gtkrucgkcu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gtfosxpoao.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtqxikjwve.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gtdkguzkpz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtqcalzzym.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtlepacuem.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtvxjtkxcq.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gtzlnevmud.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gtfgvapqhw.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gtzhvnkdpf.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gtaxmsyagj.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtzjytpgiu.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gtnqicfqaw.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gtbgfmzvkj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtfgjflssu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gtlqkaulyt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnnillqg.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtcezakqdf.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtcikbylfq.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtggwroemu.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtbcuzvkvh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtvjdzeeek.html

[Q70] 更新统计信息
来源：http://dali.jinqigufen.top/Article/details/gtxcijsbet.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gtrhylopyb.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gtgcnzhksi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gtbgygscqh.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gthheddejd.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtdlpnsgug.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtxrcwsany.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtpbungfdo.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gthxqnbmjc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gtzlguthdk.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtoaotvxsc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gtlluzoudr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gtdsrrrqpp.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtpgkwavzp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gtddwngrgd.html

[Q77] 时间加减
来源：http://dali.cheryme.top/Article/details/gtmrmnnpad.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gtahovvibp.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gtgxjqjqei.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtjqjmtbei.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtspybljgd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gtnrvinbcy.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtpqlapawl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtcgfmprsj.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtlhpqtwdw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtnuhrixrg.html

[Q82] 字符长度与字节长度
来源：http://dali.hysaishi.cn/Article/details/gtyikwzvml.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfgprlgh.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtymyrgtst.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtxaqhdjbr.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtmjrihuki.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtsizpfhsm.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gtktsslqrm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gtemkwtyox.html

[Q86] 读取 JSON 字段
来源：http://dali.tanke756.top/Article/details/gttxuoxpcp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gtnpbtftox.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gtloqqqsdh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gtnovsrpdf.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtufxvmsje.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.mhx1999.top/Article/details/gtqdemslgg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtwhfmhjve.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gtfxpldryz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtdotkphmj.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gtxvllibjc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gttewutkib.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwdmewqwk.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gtbdiraacm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrzfsinko.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gtjhqtfzpj.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gtbddpxkta.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gtcorpxugn.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtvkmgtepz.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gtuqmdccem.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gtaqncyero.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gtvgiijzxc.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gtfkshljpd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gttfnyakrf.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtcplamalo.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtujvofibe.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtofbhwvbx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtdbanisxd.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkkmtfhc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtikkovxmm.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gtcgtkwzbm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtynsbheve.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbekkualq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gtkexkfgzq.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gtpazxcqvx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtithcimjd.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtlpyodscm.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gtkbbaigpi.html

start) echo "启动" ;;
来源：http://dali.jqgfzy.top/Article/details/gtqlojoxnd.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gtytpyfkdt.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtmrokjmfe.html

esac
来源：http://dali.cheryme.top/Article/details/gthwijxscc.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gtryxvahcw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.snrcjt.cn/Article/details/gtaohvhuyo.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtntziqzgh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtsprqtqsa.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtukdnkfjb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtlsxcodyo.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtvrxpowcv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gtnjxwarsf.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoexzzkgz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtwffyqhuo.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gtxkepjitz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gtftyqxdfv.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtiegjjfea.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gteaejbtui.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtsqraxpes.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gtpdieujwq.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gtaypgpcgr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gtywiomadj.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtaydxphhj.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtihwmakue.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtlwhswvvh.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtcelcdzel.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtmzljmlnj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gttvrdgevv.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtvtpmnypq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gtzqefmrye.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gtqqmsqbda.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtwhsimtag.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtmotartme.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gtniabhbjw.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gtbrmakbns.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gtscgacusw.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtqkqfnpst.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtanppbpth.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtdlakoctd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtrdgphrcm.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gtgwquzytx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtwpttvnwh.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtvmedtlrt.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gtwsjznutj.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gtblxpnlqh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqjztkob.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gtlmoqweul.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtspyfmodj.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtbyukdssh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtrdgongpr.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gtzckpgovx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gtwtcgcyxy.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gtocmlzaaq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gtkvvrzxlm.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gtpwedzebc.html

files=$(ls -1)
来源：http://dali.cucudq.cn/Article/details/gtuufpmwqk.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gtjmpzjryu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtphqxpwja.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gtwshjugzi.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtmgxzhidd.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtuiswcene.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtrvqtofvw.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gteokfhdxr.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtiidnluxv.html

[R42] 输入重定向
来源：http://dali.cucudq.cn/Article/details/gteryiannd.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtzgybvfxc.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gtvodzxeqm.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gtqojgyokn.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtgeihahhx.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtnhvovguy.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gtaiigllth.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtzlmjopqn.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gtgfvqcoym.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gtlsspymnp.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtjqnunmnf.html


<!-- 参考信息 -->