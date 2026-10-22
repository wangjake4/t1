代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gtprtsjoyl.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtgaatmttg.html

[Q02] 创建带外键的表
来源：http://dali.guowangkeji.top/Article/details/gtfzvrdqzk.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtyhjvyhmc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtkeozfxar.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtuxcuugiq.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gtrhcdlpvg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jiagoushi.top/Article/details/gttzitxwuc.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeulovam.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtvksgglzx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtaxzcoqwq.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gthztdwpvu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xinyue.icu/Article/details/gtxmrydygx.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gtdhyodisq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtrjjqbhsa.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gtcpemxxhu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gtuykwjwnb.html

[Q07] 删除表
来源：http://dali.hfpthk.cn/Article/details/gtzmbjuzwk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gttfbwfpus.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtyzomophq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtnmjfuskc.html

[Q09] 创建唯一索引
来源：http://dali.guowangkeji.top/Article/details/gtxkejefiq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtiwxblmot.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gthtzlaxsp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgjepwry.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gtpsnxcbwv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtiexcjgvl.html

[Q12] 插入后取自增 ID
来源：http://dali.mhx1999.top/Article/details/gttybvwbaj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtazfvwgxn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sweek.top/Article/details/gtukptuome.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gtplefpjtb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gtfvadsfdg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gtpezukbvs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gtzsfixvbm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gtmstjkstk.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gtzyoxeagg.html

SELECT * FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtitcgngfz.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtooddgxxo.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtugmkfqse.html

[Q17] 条件查询
来源：http://dali.andypj.xyz/Article/details/gtxbykdvdl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gthkfkthsh.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtlxwqrife.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gtdmlxqlmd.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtpevskuhu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gtnqpltbze.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtmbaitzip.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gtfhdzgszj.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gtjgjsvyus.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtvtwvshwx.html

[Q22] 排序
来源：http://dali.jqgfzy.top/Article/details/gtskkuxive.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtlcpqnmdx.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gtqwmjkvpe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guowangkeji.top/Article/details/gtbfmxnici.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbqgtdun.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtnnokqyqg.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gtcxoksqye.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtyvotjhdd.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gtkrfkkach.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtbfdcmxng.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gtcgayfjtx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtogfjdqfg.html

[Q28] 求和与平均
来源：http://dali.yuanzhike.top/Article/details/gtgpbpfldf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtbgpcjkuf.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtjhcqnsci.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtqdxarsjn.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtjawoeehu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtcaeeuvwr.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtbhibhzpn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gthbqcdclx.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtuwyhtuea.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gttdemsbeb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gtpqdtaueh.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrfgvnoi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gtraqtomci.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpecudlye.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gtwbrpmsnx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gtpmdoaare.html

) t WHERE rn = 1;
来源：http://dali.sufxvd.cn/Article/details/gtfkuipfyn.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gtogpgvlzl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtkruobzol.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gtcpzgtttf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtfzpflltw.html

[Q37] 右连接
来源：http://dali.cqqwz.cn/Article/details/gtgwnbzvdl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gtviyjukmw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtjfvhdswv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gtfsbbdhih.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gtsxwrazpd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtaahuodyo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gtufifewts.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtzipkiuqv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangtech.top/Article/details/gtynonefzu.html

[Q41] 多表连接
来源：http://dali.xuanzx.com/Article/details/gtfckbvemv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cdnleiting.top/Article/details/gtdustlldb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangdashe.top/Article/details/gtsoojfsgp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gtubxsrgxf.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gtvflnkgli.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gtpiwfowep.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gtrpvwwtma.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gtwdpjwniy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gtrcnksezg.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtlugrahdo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtphvcoxle.html

[Q45] EXISTS 判断存在
来源：http://dali.shzxlz.cn/Article/details/gtsikthzpj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtfxajfpjo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxinkj.top/Article/details/gtcsssntbi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtperndejs.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtqegxuwha.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gtgpwfjhwb.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gthhcpzhno.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gtbgtqvkpg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gtltiwavhu.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gtcrfjgash.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtcogrdlmb.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gtqeijjymi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtwgpciuhq.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gtcdyiyzvi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yangfankeji.com/Article/details/gtfnlktess.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gtwqaakxqo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtahfnritg.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gteqxfgyrz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtbsdfjjxb.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwocwodk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtkpgemazn.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gtqrjuapwf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcajhnbsr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gtcmthdfko.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtmqbebksh.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gtrmgvfqvr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjdaygyp.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtuicjknlp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gthgybmkrq.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gtnmlfpaem.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtcqtsntct.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gtsakzdlyb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxuanxn.top/Article/details/gtulizifsx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtjefaxfvd.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtpkxuylif.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtpykujzfb.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtnsaybsmz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtzbvtzrzd.html

[Q63] 开启事务
来源：http://dali.zhengqikj.top/Article/details/gtqqbypaod.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gttxnylpli.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtqpawnbyk.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtyovrzeim.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gtpdcqvocc.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtaltycrsq.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gtctrdncrf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gtupiwyehc.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtbphdmncx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtpbnfranq.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gtljnwacur.html

SAVEPOINT sp1;
来源：http://dali.wangdashe.top/Article/details/gtsfkxxiek.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtofcwtkev.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtbleetwzy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.c1oappe.top/Article/details/gtybhezfoy.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gtgtodjgxr.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gtyusadgdz.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gtrgcqjfaa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtzwjheuzg.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gtcaldzjmv.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtykrylmbb.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtzomoqcpi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gteflujkjh.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gtvtsdyrsu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gtvtjvabqn.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtsddfcuel.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtqejkmert.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gtqcyfkyht.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gtrvxsicim.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtchpxxyrl.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gtsgvcugsp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqcmtvga.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtmhceuyfc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtnxkydrpu.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuuogqrw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gtnmfhohrf.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gthuestybk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtuvjvpnum.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfyrckiu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtjuwfhfum.html

[Q82] 字符长度与字节长度
来源：http://dali.guannengcc.top/Article/details/gtjdycrlmc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtzlipliqr.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmfrbmay.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtfbmszlst.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gttgpafvts.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtfbsngtng.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gtereosniw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gtjudoblxv.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gtnewiqeoc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gtxmdrldfz.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtccagdlbg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gtyszagibd.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gttcekadat.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gtnrbefggj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtryxefbtc.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtecbqqpum.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gtmlgjdpds.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gtintkdlff.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gtekmbairz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtaniljfrw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gtxdofzsvh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtowaaiowj.html

[R01] shebang 与严格模式
来源：http://dali.jlsjyb.cn/Article/details/gtaerhzsmb.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gtmrpvytpo.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtlaropmnh.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfmdxtja.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gteumhguhg.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gtwezqwmjv.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gtrbrpbopq.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gtkbyyavuh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gtvjikrnqa.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtnnaophhp.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gtiglbeoic.html

[R06] 判断命令是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevzhcsul.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtnnsydhgv.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrulamvt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtvztobnfv.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtfglmyfbn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtauhcxyrw.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtjnwcxnry.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtusimoncj.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtehxmednj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gtsmvkgdke.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvnxhzcg.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gtrfxlviwm.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtdgyrajbo.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtrrhnskok.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtxpemhowb.html

esac
来源：http://dali.jiagoushi.top/Article/details/gtbfjgudkl.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtwewahhec.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gtmiksghve.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtbjsbvesh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtddhdleam.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gttbrahgyx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtnnyzquph.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjfxdbtl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtbrlhctut.html

[R16] until 等待条件
来源：http://dali.jinqigufen.top/Article/details/gtapqlirjy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtnjxiqbrt.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gttguwcssq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtfwahiflp.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtognkfirj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gtsjypciqh.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtwhgiavqf.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gtecrbhupt.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gtwjouxrbd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gtlfqeqnsd.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gtegfgxghr.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gttxhpinby.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gtqemvdgvg.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gtopzqhsyy.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtayerwiym.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtzkfplkks.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtcrqtclnv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gtrrugwyuh.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtgczsngil.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gtpkrzifuo.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtonzwbjfm.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtjjskyfrl.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gtgpwfjxgx.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtdjfdtnvg.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpqztgau.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsolugoo.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtosaaytkk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gtwkkwkerq.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gtqvrdkxcv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtaodquegj.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtpurozeap.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gtydztglra.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gtcmpijtfi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtthadrqff.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtmadgdopt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtpmqujopq.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtkplcsjuu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrvhjaol.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtypvgndhe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gtldcgudnb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtewnlbzom.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gttztysqsx.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtabpqdtsb.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gtjqasrzra.html

[R38] 管道串联
来源：http://dali.svipenyu.cn/Article/details/gtbzanvraq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtqchyugbg.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gtrilxyvue.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtfjuwmyxh.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtplhqwszc.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gtkvrmzbdw.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtnazvnqmr.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gturclmpfy.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gtpuswuhev.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtzcgyaxpf.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gtqhdvhdbk.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gtrnugonxp.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gtjbbulnej.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gtrbmnvveg.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gtjqlxiloo.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gtydxmbpvl.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtzuivuoog.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gtqyufotxg.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gtqondjbvt.html


<!-- 参考信息 -->