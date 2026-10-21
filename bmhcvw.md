代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gtdrmwrgtj.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gttvahtnqy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gteelosckn.html

[Q06] 删除列
来源：http://dali.wangshuangyany.cn/Article/details/gtzyopouki.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gtkdkixwbs.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskewcbtt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gtfeqitsqy.html

[Q08] 创建普通索引
来源：http://dali.svipenyu.cn/Article/details/gttaunlbpz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjiiasna.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gtzfrznnli.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtvhdogbfj.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gtoeootlgn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aizwys.cn/Article/details/gttdhqijri.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtnebwnrrk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtkjrpnigm.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gthkdmpout.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtqcdveofi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gtxfjfdakt.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtpmzglssc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtulqbymmp.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gtcgjpynhg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gtmoyvcqwy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gtjescdezn.html

[Q15] 查询全部
来源：http://dali.shangyingyoupin.top/Article/details/gttdvvqsuz.html

SELECT * FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtgavzoimq.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gtxqziqlno.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gtbslooncw.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtwemdykgt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gtweiupxwj.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtrzrqjvpq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtzujcgiqr.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gtdjxrqsgx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yangfankeji.com/Article/details/gtbymeulru.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gtfhpuarwq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gtxlcxawhk.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gtxwkdtrsc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtijuvpbfr.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtrxasjcji.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtpmkitonl.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtodulxujg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gtokpypnhd.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gtmnkhziah.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtynmoalld.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gtuevmyhbk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gtvkdgzqoa.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gtpmzfbwaq.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtmcpofozm.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gtfiklbmpw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtaepkkczz.html

[Q28] 求和与平均
来源：http://dali.yonumen.top/Article/details/gtxronomdo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtofhxhodr.html

[Q29] 最大最小值
来源：http://dali.meibo888.top/Article/details/gtpsxgturd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtbiayapxk.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gthxxtspwd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtmvhitaub.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gttilcbekw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtsuordtea.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtwyyuccnl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtkpyzsaoy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gtzotfayrp.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gtrydkkdej.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyskvzfm.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gtzudfveag.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtkkfznzls.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258.top/Article/details/gtzzucycfa.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtedpotbis.html

[Q35] 内连接
来源：http://dali.xylfe.cn/Article/details/gtmxptxred.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtxqcrdbfi.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtdnxxqpmc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtuzhekxbn.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gticezzqli.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gtsvgjnifh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gtoaatubzs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtlepjhatd.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtiqhxpmeg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gtgtnhwfvj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gtahwcvvds.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtmvlpoenq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gtihfucsvi.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gtunqnvxly.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hfpthk.cn/Article/details/gtkrwyinpe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gttcmcycjm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gtvynyvvhe.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gtgjxzdgsh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gtknkhfobo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtorgcgdlf.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gtoibalaep.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnghkkcf.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gtabsruoef.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gtynxrpabb.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gttvvycyel.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtfxldjzdd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtpodpxajr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtmmwzebvd.html

[Q47] 与平均值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwmxfakb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shuidangran.top/Article/details/gtnlwmdeki.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtjnvyulae.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtxfaugjer.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhengqikj.top/Article/details/gtfjninznw.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtmprydtqi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtlmjpcmih.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gtecxjgkjr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gttndiyomi.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gtmpxsqfbn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtlicqbzon.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gtjegtcwdp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtgquclstv.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gtfndfcyot.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gthgbehtyw.html

[Q54] 清空表
来源：http://dali.hysaishi.cn/Article/details/gtcgyfrtww.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gtvixjvmvy.html

[Q55] 排名（并列占位）
来源：http://dali.nanxinkj.top/Article/details/gtvdwosmob.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtkfhfvybj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gtvxpxyiuc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtipitqshw.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gtpeutfrbb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gtpyuelwfu.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gtsldwbbhi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtbfsubaev.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtextdfsla.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtlynpmycs.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtepkqgifc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gtbpcfzavy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtitbcsjuj.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gtqgtnjcok.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtwwagnjhp.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gtejsqgihy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtktjjdsit.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gtbqoqfhzu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gtrkarckyj.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjylobzdr.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gtabemzzrm.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gtlmlhxwqm.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gtpckoulyq.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gtlqwwqdkf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtjwayrtyv.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gtzovxabrq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrexnnqvp.html

[Q68] 保存点
来源：http://dali.pengpengdd.cyou/Article/details/gtnaeiobke.html

SAVEPOINT sp1;
来源：http://dali.tanke756.top/Article/details/gtvbaneyrj.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gtoqzvsjlf.html

[Q69] 查看执行计划
来源：http://dali.fengsongda.top/Article/details/gtulmndwfx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtygwtrmmi.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gtzwcgjwar.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gtojopsumv.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gtwopymerj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gtkmbspbit.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gtwicmbobh.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtpifmesdg.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gtthxxroan.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtjmwckron.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtkwmgcred.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtkjhphldz.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtfmcxpqmg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtwiurkiau.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gtegnxtdgu.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gtcablpnzw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gtmvvnurol.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gtdkaidzwh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gtgoimijmb.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtgbpogmpo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtusrfzjio.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtiidkqemt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gtwrpguitg.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gtvskjjijw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gthoewmcub.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtevhdkkzs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gtygyqgsvu.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtvhtlsqgy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtfklphuif.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtytantdep.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtvdhitljj.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gtbmlzedpx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtinakvimh.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gtepjfycrq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gtutugznia.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdanhwmyn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gtdkbjxyvh.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtyfizxgrk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gtdsfvdemz.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gtqomvlpxd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigufen.top/Article/details/gtwtaenhnd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtmuvnfwgm.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtclqkevpu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzjiibou.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gtqoquhpnu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtkocvehxd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtvddzdhnm.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gtbbjcdanp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtkdqwwizc.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gtkpvkrbox.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtilpuvxwe.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtawpswkit.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gthydnxudr.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihahfzly.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gtxmggufku.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gtwtbxunfz.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gtfchorfua.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtazkoxpdj.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gtyrgjtxtq.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfpnodvs.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtqvcryksj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtiizvxpny.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtabjjupla.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gturabfqgx.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtrrvhwqso.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gtkhauxuxl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtydwwfsdp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtfifrttpe.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gtdqqgphco.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gthkkcjgys.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gtinlgdjfi.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gtqfcpfhon.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtdrpxlpim.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtqvdaczhr.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtegxxdlie.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtubcvopje.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gtvqmcruwd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtxnoiznab.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gtjmjvzcmk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxfamlcm.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gtcnrdfanb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtkasllsxd.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtqmvevjfd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gtrddykikw.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gtlmcrczfl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtyhbjlgbl.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gtfmawpciu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtuzaarnlv.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gtpeijkbrb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtirnixcvn.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtutjemjaa.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gttfltjwxv.html

[R20] 关联数组（字典）
来源：http://dali.wangshuangyany.cn/Article/details/gtnziincak.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmoojmdx.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtufnnqjrl.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtzlbtjjer.html

[R22] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gthpvfssdp.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtszoetmfs.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtuwyexvws.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gtypkspbuz.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gtpaykdcpq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gtfghzxbhf.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtjhrjjyil.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gtpatdzzln.html

[R26] 命令替换
来源：http://dali.haohaochexian.top/Article/details/gtcecpofrl.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gtwumasbtd.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtqovapgrv.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gttzejamsr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gtqeuqkslo.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gtyelrntlz.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtmixyjgsq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtdynvylig.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtoeqnekiw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtlbxxzisb.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gtfjjdboxf.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gtvrjgecws.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtqkjzmxzq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtetyxrjfu.html

[R33] 捕获错误并提示行号
来源：http://dali.sysykeji.top/Article/details/gtrdsrkmwd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gtocqnzojo.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gtguquwxdf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtdvdqaxvv.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfhosxxt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gtnfqsudlu.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfexsvxc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtznaefdlm.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gttxvvjzpg.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtlwhnzrwg.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gtikytswyl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gtcsuzacga.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gtlumvzrqf.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtlqlwvfjt.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gttoeqeoos.html

echo "log" >> out.log
来源：http://dali.guowangkeji.top/Article/details/gtcezjyven.html

[R41] 丢弃输出
来源：http://dali.yanxiufei.cn/Article/details/gtcgwrlwri.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtfhgghzcv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gtuchnknhk.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gtvlodmtdw.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtfihtfibc.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gtqpzqxlnw.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtjatvneuk.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gtqfzvyxxv.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gtupzecwip.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gtrjjjenvi.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gtxcyrriub.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yueranfly.top/Article/details/gtenaclode.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtbmvsymcc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtstmttxfb.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtzlmktwmh.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtdcwwlegn.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gttbzixyfe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gtxhugxyqg.html

[R50] awk 求和
来源：http://dali.meibo888.top/Article/details/gtyipenxan.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtkhgkotqx.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtfclpbptu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtylowwlph.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtwdplbxel.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtnynwiwwe.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gtsrnvnksr.html


<!-- 参考信息 -->