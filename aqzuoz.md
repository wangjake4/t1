代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gtzdszhurt.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtichtajwj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hysaishi.cn/Article/details/gtuscrpesz.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gtwxbesuio.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gttqvjefbn.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gtsjsvwhnk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgehsdjyt.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gtxxgsfkxr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtxyucmdjk.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gtqwxbzjvx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtdlbznkis.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gtfmurcmob.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gtgdrmpjsi.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gtvrgacmwr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtnswbirpo.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtociiitnq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gthuxxqnxz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ehwqpu.com/Article/details/gtwnrjqzfb.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtkwpauvrr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtmfqupbud.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gthxbeqkrq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gtmhpbwavj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gtzbvzxjkl.html

[Q15] 查询全部
来源：http://dali.yuanzhike.top/Article/details/gtfzejhzuy.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtlppjcedz.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gtikfsupzb.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtznrjujes.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gtpylhbxqo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aizwys.cn/Article/details/gtxbnomiqq.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtwrqtvohs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gtpwyptmht.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtqffggzzl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gtjxlbqxsf.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtezuefthw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gttbrfmmle.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gtkuizczwy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gttkgfcevg.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gtwrzryxji.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gtvvlixbho.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gtksmrbafv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gtuekhbbra.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtczpcytcw.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtmujnggqq.html

[Q25] 只取前 N 条
来源：http://dali.shuidangran.top/Article/details/gtwrchxpvr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtwmjzvonf.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gtcocrvzpz.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtihwbpqnf.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtocdvmzik.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpeskslbb.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gtouquxshq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtmieswxzz.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtzqpssyha.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtjotbzlwq.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtjwpgywkr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gthnsxroyu.html

[Q31] 分组后过滤
来源：http://dali.fzhhl.top/Article/details/gtqotbutsq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtdmkfkusb.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtbwyedodq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtfxzmmioo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gtxtjhlrgr.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gtrdfniubh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gtgjxiqnpf.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gtrxmcesxk.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtjkadmwvi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtyytjimms.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gttclfjdqt.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtbqwhygyc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtldzjdnac.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gtvrceuxad.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtgnpoljjx.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gtddquyfmg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtfmhvqzyg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gtwjnokddg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gtbsohqrim.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gteaediavf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aibaodan.cn/Article/details/gtmrwjurtp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxzeljmu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gtuctohvnr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gteukrizqj.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gtnxsiwtmg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtanfqxabw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gtftwjkmls.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gtffcznhhn.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtsxuuykon.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ybcxt.top/Article/details/gtuevxclas.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtxoylbqtz.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gtbopcpllr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj202588.top/Article/details/gtoxxnufju.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtkiscmonb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gtwsrstnrj.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gtsgugwdun.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsrtczzi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtufetdama.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtqemluhqn.html

[Q47] 与平均值比较
来源：http://dali.xuanzx.com/Article/details/gtvwishlgc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtpfgxetxz.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gttfeotpen.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtqyorlxzi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtsdxbnicb.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gthuvbxcsq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtezkbinld.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gtrxidrzyo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gteizlzkjy.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gtmlgrmhgr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtookqnzll.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtdiqoqxwj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxwqhmlj.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtcgyhoara.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtshumrjui.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gttdglmvys.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtpzdvmvui.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtldisqprj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtrtwqjpau.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gtbldzuhnf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtifdwnctd.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtaugycndr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtpfhcosex.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gtkyzjmvpt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gthohxmpfa.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gtmpcdbuqi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtobymjpvb.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtaljrvkbb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gtehdyevji.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gtcszveuum.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtumxvkwdd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtzrwijvwo.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtlvmlkqxn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gthzwgnvgn.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtcfhnumic.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gthllpbgku.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gtboaovgtt.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gttixumqod.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiyfhper.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gtxnafwamh.html

[Q66] 行锁查询
来源：http://dali.yangfankeji.com/Article/details/gtqvupchqw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gtigbikzev.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtjmqocirs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtuzfzeyxw.html

[Q68] 保存点
来源：http://dali.gzhubu.top/Article/details/gtwnmesbjq.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnwzlzwq.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gttbeewtvv.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gtuiruhnbe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gtwlwupqld.html

[Q70] 更新统计信息
来源：http://dali.jqgufenzy.top/Article/details/gtwtwykvqk.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gthekjfrig.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gtsgrklfiv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gtgktavohz.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtqgvmjwia.html

SHOW INDEX FROM users;
来源：http://dali.tian-w.cn/Article/details/gtpgjroavz.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtheyauhqj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gtbhhifnkb.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gtvgxrpmwn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtlknwqemj.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtygspuxgh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtlzbqtuzf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gtrkffyomi.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gtmbopinmh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtwwvrfxft.html

[Q77] 时间加减
来源：http://dali.cheryme.top/Article/details/gtbyuwwlek.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gtmuniydii.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtaokpyfur.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gtkypfhrck.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtrccfkzfg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgaqgsyb.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtmxcpnxij.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtanfnsnzf.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtjgxyxvde.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtxodggbho.html

[Q82] 字符长度与字节长度
来源：http://dali.dashuyun.cn/Article/details/gtsceghmye.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtwgmynoww.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgruhzit.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtjggxphoo.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gtqbthdkac.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtjnqvcuth.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gtwpwvvaux.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gtvtsembdt.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gtmydgwshy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gtlyhalocv.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gtukabzoua.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtflhneicr.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gtrevhdjxz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtrviuaesm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtazwudjvv.html

[Q89] 判断表是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvurzfokg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtxmyfokky.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gtfawrcafi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gtqbpvlcaw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlurkldev.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtpqkzzgiq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjnkygsur.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gthhurcldz.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtevxmmidd.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gtlveftykv.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gtulqcrldv.html

name="Tom"; echo "$name"
来源：http://dali.xinyue.icu/Article/details/gtwbosjhdy.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtbtobmrbz.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtbjhknvjo.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbzjohyw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gtwvidbgin.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtpgxpuszw.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gtjtsvcjde.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gtejsltvha.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtblpeethn.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gtfmpszcvm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gtryvsmdtn.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtpcyxterz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gtsaeeishp.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtujqbodzq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gtwifoszdd.html

[R10] 正则匹配
来源：http://dali.xylfe.cn/Article/details/gtnvukjkva.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtmalqajoj.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gtiqujedof.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtuitanpls.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gtvuhimrsn.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtyeypsauu.html

*)     echo "未知命令" ;;
来源：http://dali.9152youxi.cn/Article/details/gtltugttjh.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedrquwaf.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gtsqpudglz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gtirxxbxvi.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtpgmagirt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtjpqcalyd.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gtolcvantd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtfgyxxopq.html

[R15] while 逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtsetydbhh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtebtuwjwg.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gteocggosd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtrzibdldq.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gtcpapkfuv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtnezebyfw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gtgqbahzfr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gtjioprmmj.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtrrjdowhh.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gtgczycoxq.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtftziicht.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtwveiyess.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptmodiys.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gtatkmtqab.html

[R22] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtoktphrgo.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gtxbtogjxs.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtzvrcvfwm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gtcabdocod.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtvwlcvdkl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfggawmd.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtzbhbqmdp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtusmbuvzk.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gtssilvpfm.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtkjscvxst.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtnxgmkzzv.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gttquvrvwd.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtiebodakf.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gtktujjqvt.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtyribcdlq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpoixwct.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gtnqamdshg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gtizzmogtu.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtptjunszb.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtjvoaxnxw.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gtxbuidyji.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtotvkqdft.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gtcwhrfhwk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gtuovkopjg.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtegfvbqod.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtbcullrtk.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebhervtr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtborczveb.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gtbdbdqmfk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtwngoksjs.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gttfrlnngj.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gtepdtuggp.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtthythoxs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtjizkanut.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gtnhdpcsqs.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gtzoxeepll.html

[R40] 追加写日志
来源：http://dali.aizwys.cn/Article/details/gtptjqcowj.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gtgobjqdbq.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtfybyjkar.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtbdkssazo.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtbiizqqsa.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gtcpwcezip.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gtcgdszbgg.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gtniumiogx.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gtxudjafbt.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtedzmiuhi.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gturvfyejj.html

find . -name "*.tmp" -delete
来源：http://dali.dashuyun.cn/Article/details/gtpuiohzpv.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gtczhsaaea.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtpvvhzovy.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gtxddaiyfw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtquuvpofs.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtkkokrasz.html

awk '{print $1, $3}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtavhovewl.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gtqgsdjesy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtnknfefng.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioinlfyc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gticdomdhx.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtnyhmqbji.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gthccumbaz.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gttgqinjvv.html

wc -l a.txt
来源：http://dali.sweek.top/Article/details/gtpdsmlsdn.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtkrbidvnr.html


<!-- 参考信息 -->