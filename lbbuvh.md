代发 wailian999

);
来源：http://dali.meibo888.top/Article/details/gtortbeixk.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gtswwiaoax.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gtdxzqwwkl.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gtujcqcccx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gttxntnmns.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtwmstawhs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gtamvfewib.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtwqprxncr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtcrkxrwjz.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gtzubupwan.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttavbevse.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gtujkrwmrf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtjyyxvsvp.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gtpxgieuqk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtbkqhcbct.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gtdqckpmzm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtwxsiccpq.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtenbhaclh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gtmvdnpbkw.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtvfvwkcid.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gtigbpoysk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gtanbsfizs.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtlwovkpdq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtctnhnjug.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtzhfwpzgg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gtrtgokpty.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ivvv.top/Article/details/gtupgtriwz.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtdripahrd.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthyiqemhi.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gtqnuowlnm.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtpzrfgbqn.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtofilmilf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gteoxgrtjd.html

[Q18] 模糊匹配
来源：http://dali.yuxming.cn/Article/details/gtkihzslms.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gtmzxpbabm.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtwkqeroau.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtckotdstx.html

[Q20] IN 列表
来源：http://dali.cucudq.cn/Article/details/gtngvivlvq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gtipnqngho.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gtwrgbbwxi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtflkzymtg.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtmjrpfdgm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtryrfrysh.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcistxjvl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtudzwnpqi.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtpbtowcpw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtuiibatto.html

[Q25] 只取前 N 条
来源：http://dali.pengpengdd.cyou/Article/details/gthudvcroj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gtirxbpbsp.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtqkbnejmq.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gtdyxsqdng.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gtqcyvjtkt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tian-w.cn/Article/details/gtdueikhbl.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gtwgsdmqsb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtiverunpa.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmnoecqy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gtbswyreor.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gthoifpgia.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtfpqzjfmv.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gtcrmszror.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.0kj1m.cn/Article/details/gtkoepyoky.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtozgyxwil.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtnjgkvffl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gtgxsndqqc.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gtvjjayill.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258.top/Article/details/gtbyblrqjk.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gtfgyjlqfi.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbealtgov.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtvcvbgauq.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gtuairjovw.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtuflmoglq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gthblthjyu.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtaakqcjkp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtszptkbox.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gtcnqdpcvh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtvoapwurh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtbskxitgh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.andypj.xyz/Article/details/gtuzsxxjdt.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gtnvdemjdv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gtymznqspn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gtztbdgrqj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtjuylxikh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ydzc1.top/Article/details/gtkawfiwfc.html

[Q41] 多表连接
来源：http://dali.yonumen.top/Article/details/gtmjgbzaux.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gtwftqxoeh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gtrklventl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtshzqbmpr.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gtbtsesbaz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gtajqhnnge.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gtylqgifan.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gtpntutbms.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtyfrpblmx.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtfguwttjr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gtljbrdgmp.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gthctdneqm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtbhrtvjzt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtbwlmutia.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtbqgtwcqi.html

[Q47] 与平均值比较
来源：http://dali.zhoulong.xyz/Article/details/gttvoqvhsm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gtqoqwgbft.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtfbbifxqa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jiagoushi.top/Article/details/gtysycdjgu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtcthxhhiq.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gtenrbqefe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gthsnqkejk.html

[Q50] 批量更新
来源：http://dali.c1oappe.top/Article/details/gtuxobacbu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gtxrujfxnn.html

[Q51] 用子查询更新
来源：http://dali.0kj1m.cn/Article/details/gtjyserlvl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltohuldj.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gtmpwinygn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtbecujfof.html

[Q53] 按条件删除
来源：http://dali.xuanzx.com/Article/details/gtlerbqaqn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gtcjuhtnzy.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gtyaqjahxg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtvinbrgyv.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gtmstxxqpp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtgfvdsfeo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtngqkevju.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtznasehhu.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtgbysbtnl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtcxoeamcb.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gtzdkpnfwi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gtogelgwuc.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtjqzhhqom.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtcqlaatrv.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gtnrcghyzf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gtzkaxqhra.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.birdmap.top/Article/details/gtqqayxfuy.html

[Q61] 移动平均
来源：http://dali.vqdsnc.cn/Article/details/gtdvwvlsuz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtklvtkffp.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gtzasvbntr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtssrlpxmx.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gtioecujha.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtdirysmja.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gtrkzizcse.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gtxfmpudxo.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gttarwcpci.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtidibrnrb.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gtqrxcfpjh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gtmombdcfk.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtgwsuglfv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwademvhe.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gtxnyiipcj.html

SAVEPOINT sp1;
来源：http://dali.jiagoushi.top/Article/details/gtolacdeqb.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtqwmobhht.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gtuazndiyy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtllewqbaq.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gtzjofpzgu.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gtnripxkiw.html

[Q71] 查看建表语句
来源：http://dali.tanke756.top/Article/details/gteldokfdq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtzyldqlkd.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gtncaebfuq.html

SHOW INDEX FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckrwzjpl.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gtkbrgdrvm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gtwujfhhax.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtcammwzpf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gtwzvwnseq.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtpuejvasr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtortsavxk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gtkbmxlaew.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gtyjrnlmhx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gtjzavuibx.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gtpyzyrscw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gtpoxlrquc.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtggkulhts.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtkxcomzgq.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtpnslgaqi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtcjeocibn.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gttchjnbga.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtvvbcwbjd.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtaegojwnv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gttyktartl.html

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gtpdombsea.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtrurxskmo.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtofyvauzr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtpffmxori.html

[Q84] 去除首尾空格
来源：http://dali.fzhhl.top/Article/details/gtpobsqoam.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtfcngnjmm.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtltlvhzji.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtkcryijsc.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gtnmohewrz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gtgkkgduhy.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtdlpmlfea.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdiuftzn.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangshuangyany.cn/Article/details/gtbistjhxg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gtkyhfezdx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtgqmbjtrc.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtbpsobjfp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gtkldkiqlj.html

[Q90] 生成序号列
来源：http://dali.feifeiyinyue.top/Article/details/gtbwigtxvv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shuidangran.top/Article/details/gtceftqpmy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwgebcatx.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtzclaxeat.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtshchcxzb.html

[R01] shebang 与严格模式
来源：http://dali.hongshengwenyu.top/Article/details/gtywaxqzva.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtchmwxvpq.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gteufzulbu.html

[R02] 变量赋值与使用
来源：http://dali.ydzc1.top/Article/details/gthqwteiqa.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtyjogthws.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gthbzvbgoy.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gtbisvluqo.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtmrjkpqii.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtgnhqnunp.html

[R05] 参数默认值
来源：http://dali.yuxming.cn/Article/details/gttbhtkgdv.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gtygtkgpxf.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtqfelahhn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtklbjxseg.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtliukqpha.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtsmtlctyi.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtyfbxucux.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtjxygdcfl.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrpcgdvw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gtwbbprmsz.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gtmuifiwhz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gtqpacgbxu.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gtruxsqcgg.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gttsjdfdze.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gtuwcvhevl.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gthikwiuio.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gtcspeagki.html

esac
来源：http://dali.guannengcc.top/Article/details/gtgkhatkoz.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gtbkbqiosn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtthgaonuw.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtwqcwwoyw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gttiwvmlbs.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfgpbnkf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtbywvhxfc.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gteoqejoyl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gtneffpozg.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gtnmmhdhnt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbghnhvkg.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gttowuikif.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gtwztqnlhm.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtveqfdblo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gtyebeladm.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtkbkmcftk.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gtiutldivo.html

[R20] 关联数组（字典）
来源：http://dali.jinqigfzy.top/Article/details/gtijobvqgp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtzbjfmell.html

[R21] 字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtrljfneyu.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gttetsbrhs.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtlxfkjsbc.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gtbemxmlez.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtgtsseffc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtolrgwvwe.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gtrnfjcvmu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gtykwtdncx.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtmahbylte.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaqisdne.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gtrmwwlzhy.html

now=$(date +%F); echo "$now"
来源：http://dali.jlsjyb.cn/Article/details/gtholoukae.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gttxobgket.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gtkrvomcit.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gtauyymuir.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gtpefvgymg.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtsplxhjxq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gtwmmavohg.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtzyqajkxb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtvjgvcaim.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gtvayuheir.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtzpnawgcx.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgrqqbvk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtaobowrop.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gtkmufpeyr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtadofurcc.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtpzrbagfp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtayorfwcl.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gthuraoypr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gtawtpjabw.html

[R36] 并发执行多个任务
来源：http://dali.cdnleiting.top/Article/details/gtepdjurgi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gtcetabtat.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gtjgaadfmi.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gtebbkqgzv.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvlshgfg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gtlrbjubrn.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxinkj.top/Article/details/gtbidbmyww.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtlfjhsqxb.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtskjmaqaz.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gtdznjqrft.html

[R41] 丢弃输出
来源：http://dali.hammf.cn/Article/details/gteeaeyjia.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gtafgynbwm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gtkbdrcfjr.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gteawklpws.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtlsxmnexo.html

find . -name "*.log" -type f
来源：http://dali.yueranfly.top/Article/details/gtulcnblkk.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gtgjdlfwjv.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gtmizqktzl.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gtdzqicafn.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtbrthicya.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtqcdilyel.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtyuwkaura.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtcdlcpusr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtacgeonyx.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gtgwcvdeou.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtaolztchx.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtohqvnevy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtxgtyjwoi.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtqjdadlyu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtzzjlesmd.html

[R51] 排序去重取前几
来源：http://dali.zhoulong.xyz/Article/details/gtcwgylybi.html


<!-- 参考信息 -->