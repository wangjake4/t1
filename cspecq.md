代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtxbpevzuo.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gtjfpknndu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gtutldjsgr.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gtgaaljkdu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gtthuzqrja.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gtuzeybpol.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gtjuecibul.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gtlqojprns.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtirdhhsey.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtggtlplrs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtbzadpuif.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gthhwkinxp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gtrclmtatc.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtzncavrgr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxyzvyra.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gtvjwjwowt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shangyingyoupin.top/Article/details/gtzbmditvz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gtwkaxqnuq.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gtpkjcohqb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtrboeaxsb.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtklldzdob.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtksdicfkn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gtdhdojlwc.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gtahskklhc.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtoyaekvjd.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gtsakolvuw.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtxncfhzbs.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gtqfrylhal.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtgjjbzxyl.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gtdzgiutoe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtywsmcrki.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gtanqpnxnr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sxryk.cn/Article/details/gtojptpmue.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtfufjwate.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtfbwvxjed.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gtmicpnpah.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cheryme.top/Article/details/gtwtyofsql.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gtozdsarbm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ydzc1.top/Article/details/gtiankmqou.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtatgamlql.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xziqi.cn/Article/details/gtwfkgnuqs.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotubyxid.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtqjlcrvzf.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gtgjwsptuf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gtaxnolxkv.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gtgquyrlhz.html

SELECT COUNT(*) FROM users;
来源：http://dali.yonumen.top/Article/details/gtrmzfbllf.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtzugrfwna.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gtwpaytwco.html

[Q28] 求和与平均
来源：http://dali.bjfxy.top/Article/details/gtgjfotpvh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtdsdcdgwg.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gtfqfezwda.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzdbjaxt.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtwelzggyk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtroqfemle.html

[Q31] 分组后过滤
来源：http://dali.aibaodan.cn/Article/details/gtoxpyinmv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtduzkpfyu.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gtlizetwhc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtsqerhnzq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gtbpndvimn.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gtlbjxoomq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtfthauzuv.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkugnrkar.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gtvmrhryqc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtdkkkblvq.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gtlotupqhv.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbkjgpap.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtlgofhtag.html

[Q36] 左连接
来源：http://dali.yj202588.top/Article/details/gtbfpiexbk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmrkgzbx.html

[Q37] 右连接
来源：http://dali.cucudq.cn/Article/details/gtoirxhlme.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtjddkjzeh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtdmlcalak.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gtrmdnmyic.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrrcgyds.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpfdqhhs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gttibskinn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtpynlldxu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtgclxqnyd.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gtagyhwrut.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gtpgbgspur.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tanke756.top/Article/details/gthjsyafmw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gtgevcxzjz.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gtaspkobjr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtepcpdtft.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthncwddoy.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwaxvuqb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuanzx.com/Article/details/gtqlfsyxwd.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gtbkndjlps.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gtexhmbfuz.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtpplqsjno.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gtyqopluzc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gtlveogmgr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gttitfghqn.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtqlrofnxq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhiwuduotai.top/Article/details/gthrvanbiv.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkhwweiq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtvmwklgyh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtatjkfpee.html

[Q49] 更新单行
来源：http://dali.hysaishi.cn/Article/details/gtrsffqzyn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtmbkprczq.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gtnvevepgr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtfdzjtrfl.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gttccdrcbo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtgwukftbp.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtlqhkimat.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtgigahjnb.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtmjbwfjdr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtwtfkktis.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gtuownssxt.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gtpnodmwuq.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gtelmfxzzh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gtttnjubuc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gtzllkbyvq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtouxnfalc.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtvdgmzhgu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtxotpwqav.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gtpzbmyxut.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtiqgvnfer.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gtrckgltih.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtgcwrcfai.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gtcrcdnxrs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gticiyxrdi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtlekudqyv.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gteluciqub.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtiyfrobyk.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtexramert.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtidoyucvh.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gteymihbbr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtkebdboxc.html

[Q64] 提交事务
来源：http://dali.wangdashe.top/Article/details/gtpvxgloyf.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtkyfsnexi.html

[Q65] 回滚事务
来源：http://dali.gzhubu.top/Article/details/gtxxeoaluf.html

ROLLBACK;
来源：http://dali.yvedp.cn/Article/details/gtadbwulhs.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtbduvgmma.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtjhsrtcji.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gtjnrsieoh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gtwgbpseon.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtmwxtztod.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtagcaqgol.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gtzokuhydc.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gtmkaqjilr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gtceowrrxr.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gthfdryydk.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtlsjpxlar.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gtmnehvmyv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258.top/Article/details/gtucqqinhd.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtfmcjszby.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gtpprycadh.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gtuhpgdllz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gteuhnlsmi.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gtrwxamrsy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gtcpmultaa.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqijsyok.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzftzsght.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenjidiqi.icu/Article/details/gtylbtduop.html

[Q76] 按天统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetyspmuq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gtqhczqust.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gthdeqotji.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gtxxwxtkiy.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtciblbscw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gtduscarik.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtysxrexow.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gtoyrajeib.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gtrrepkchx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtpojtekwn.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtpgewqcff.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gthlvhrtgp.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gtihgdynme.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtgfeuazgb.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtqcteymda.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtnbhfzwyb.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtoxwgafnk.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtzvglwcum.html

[Q85] 数值取整
来源：http://dali.xziqi.cn/Article/details/gtgcnxzvif.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiruxcpi.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gteeaqwmda.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guannengcc.top/Article/details/gtwltgyfil.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtdmeuuilz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gtaovxnzsa.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtuspawjdx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtezbludvj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtvrtkyxlf.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtcqfjkjxy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gtjrbtvimx.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gtlhfdwgpu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtibkttkpv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzlnyagh.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtupmkmara.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtotmmcsst.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gtsrouaztx.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtulpwhknz.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtqcjwmjwt.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxnfljrh.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthimtuwnb.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtmclhbjym.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gtdkyyczon.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxaigjsgp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvghapbob.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gtrdlcmfsx.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gtvmbatqha.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtblrwzdnr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtifjuoqlj.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gtbeppjosd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gtnryxkwym.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gtivyxnufx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gturlnfmvp.html

[R09] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtkqswkxqm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gtjcoojrzq.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gtdsrvnglo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gtzzdrfijb.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gtxwryjlgk.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gtzidrsxse.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gtuiicmuxt.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtxldorwdb.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtopplbbiu.html

esac
来源：http://dali.yueranfly.top/Article/details/gtjxvtvolh.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gtxigezrem.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cheryme.top/Article/details/gthappukcf.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtndiwlucu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtqybqolao.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gtnnottpst.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtumbpryej.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gtxiudqrsp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gtstwxmoko.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtpvkgpivm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtjporlqdt.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtliieprmw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtdqlifwhv.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gtiquoqhbe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtpzctoqyd.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtbwsruksl.html

echo "${#arr[@]}"
来源：http://dali.gotoacloud.top/Article/details/gtghhetkjl.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtkrfywrif.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gteqrbflpn.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtytcvuxfg.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepcbmykj.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtllzmgxyi.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutsuyofq.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtmavuihha.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gtoxmbyhjg.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtimmknjbr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gtpsynanis.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gtgjobdikd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gtrsaemxov.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gthkknowcb.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gthibppgxi.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gtmgovgaje.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtadeugvxb.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gtellerytn.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gtswxidjmg.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtwvskwmkz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpksytzw.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gtlakdnbsu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gtuokbvdij.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtbhkxhqyj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gtjzmsppbe.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gtbefpwxsz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtgwmoyiyg.html

[R33] 捕获错误并提示行号
来源：http://dali.tian-w.cn/Article/details/gtpgbvxokf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtkjhixhqs.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gttrwlggoe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtxvjoctcm.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtvzwuurof.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gthzjefcba.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gtugiocxzi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gtebcbueic.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gtywennhfs.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gtungqkiww.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gtaznnzwkw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gtjefovvpa.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gtslsreaou.html

cmd > out.log 2>&1
来源：http://dali.yonumen.top/Article/details/gtetixylod.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gthzhpnvps.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gtjmyqxyef.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtwergmlsg.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gtumsrwgwo.html

[R42] 输入重定向
来源：http://dali.tian-w.cn/Article/details/gtyusjdbsn.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtrxuxhztg.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtkfszqvxh.html

find . -name "*.log" -type f
来源：http://dali.cucudq.cn/Article/details/gtlmpaoldx.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabpgtxtv.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gtvcuuqqqa.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtwlixxzcn.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtdeviqntg.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gtqyyijnqm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtonfetzsp.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gtlwdfxytl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtnjtmaawq.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gtevgdtljn.html

awk '{print $1, $3}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtsknetnzp.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gtlnwkykkh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gtmuafxnvy.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gtddhqheog.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtnzqcpdum.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gthnltidyu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gtzxhtldps.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gtjpfulmud.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gttxjcgcst.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gtxilxlxtc.html


<!-- 参考信息 -->