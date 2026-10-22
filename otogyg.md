代发 wailian999

);
来源：http://dali.yuxming.cn/Article/details/gtfopylmld.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtlitsxjpj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtzubtmadh.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtbnzmdisl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gtlolfbddh.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gtaeoseojc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gtshqktonl.html

[Q06] 删除列
来源：http://dali.daria6918.cn/Article/details/gthhkrimmv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cheryme.top/Article/details/gtapubjgwu.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gtercthgtf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtzeyhovcg.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtowncvsqh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtppknkjsu.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gtmerjkbkf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtncdngqrh.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gtrnknyhme.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbldfuhkq.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtfkjusrwt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtaaqwuugn.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtmggeaxtz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gtbihmuqlz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gtpccbydpb.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtpsnngn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtmlbxczuj.html

[Q14] 存在则更新（upsert）
来源：http://dali.tianlin.xyz/Article/details/gtaceffufw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gtejlwwfua.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gtcamrwkql.html

[Q15] 查询全部
来源：http://dali.aibaodan.cn/Article/details/gtupwtdayb.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtkrwjoqjg.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gtljvcedaq.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtsufhjmux.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtglegmbms.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gtqikocora.html

[Q18] 模糊匹配
来源：http://dali.vqdsnc.cn/Article/details/gthomadhxe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtqubyaeiv.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gtglqcbmqm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258.top/Article/details/gtsqtiyhrn.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwditjqp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gtlbtmqvlf.html

[Q21] 空值判断
来源：http://dali.mhx1999.top/Article/details/gtknpfzvcc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xinyue.icu/Article/details/gtmyqgneby.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtxlxenwye.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtsxikzhcw.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gtkjceplrh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtgtqeadaj.html

[Q24] 去重
来源：http://dali.meibo888.top/Article/details/gtbracpcjz.html

SELECT DISTINCT city FROM users;
来源：http://dali.jiagoushi.top/Article/details/gthdvnlcwq.html

[Q25] 只取前 N 条
来源：http://dali.jianghu66.top/Article/details/gtqnuneloo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gtxyerqgug.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gtiykllwrm.html

SELECT COUNT(*) FROM users;
来源：http://dali.yonumen.top/Article/details/gtgvuhipkc.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gtlbqdrlcf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtdolwbhye.html

[Q28] 求和与平均
来源：http://dali.yvedp.cn/Article/details/gtcjcecqtj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtmvbsejmt.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtndjjlmvz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtaylfuhtt.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gtoublqfpa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtaqvhhghy.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gtivcrmeja.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gtyzyvyqqg.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtubzwhzkh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtemixxafu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pengpengdd.cyou/Article/details/gtpkilobkf.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gtnsgsgvyy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gtqmqxjtbu.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtwraztvpj.html

SELECT * FROM (
来源：http://dali.xuetiantiany.cn/Article/details/gtzxgdoirb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gtqpohwqgt.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gtzghvfzvk.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtfwouaihn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtpjmxmczt.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gtmwappbfd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtgbbspizi.html

[Q37] 右连接
来源：http://dali.cqqwz.cn/Article/details/gtqqljtyvl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtpbufyncy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gtgmoppcpk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbvzjkwl.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gtjerdytzl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtdwyfnybc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gtgdxnbiru.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gtmgovwksg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gtcmeljdgw.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gtyfdnyjmz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sysykeji.top/Article/details/gtzcczkfcc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gttekreaky.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyqrxaoo.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gtpjgzceeq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gtttrqldwl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtycuegapm.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtddrvydny.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gtwfppdruq.html

[Q44] IN 子查询
来源：http://dali.vqdsnc.cn/Article/details/gtjyiyumok.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gtazkckcrg.html

[Q45] EXISTS 判断存在
来源：http://dali.cheryme.top/Article/details/gtgcxzjclo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtuygzszvb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxinkj.top/Article/details/gtytxxdiem.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtpnhjaqiu.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtugjrnilp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvzueltg.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gttgawxlcf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gtckdpthbp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtxlegopha.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gtxcmhtysy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtirwgwkob.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtqqthvpnc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtppxwrjjg.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gthsikmxqw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gtfoezxqzm.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gttmwlnupt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtwrnomewd.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtzgmbwxqz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtvkyyhwst.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtpietjphx.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbxeixvu.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gtleqllpwl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtgxklwpcb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtenxwcvra.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtogdoqops.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gthsxlcpio.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtvueeqiec.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwwhzkza.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtpjjuuzka.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gtzwrzcwht.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtfkqjqtru.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtwgcgvzoi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtsxzxjrgk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtlzdtunid.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gtylzoegmh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtwnyswotp.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gtjerorfsf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtpalurlur.html

[Q63] 开启事务
来源：http://dali.zhengqikj.top/Article/details/gtcweuekzw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gtrbiexpgr.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjccbcfm.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gtjuzmntqs.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gtumgyavbx.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gtdluzqufz.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gtxtxxnoyv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtkfgtzupg.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtussznmgl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.redwolf501.top/Article/details/gtcgwbaxqb.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gtelefytih.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gtfetoqdcu.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gtnntnajqb.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gtopqlahsd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gtamwwsmmf.html

[Q70] 更新统计信息
来源：http://dali.xuetiantiany.cn/Article/details/gtbxhohwge.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gtaftvxslt.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtmqcauagl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtcuypfxxe.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtusibgyrg.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtmbtyeozo.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtaammawca.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gtvsugxczf.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gtfxwutnhc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gtllfzuvln.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtgehdwlke.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtmndlhipd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtdkvmsflx.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtkfadecyz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtcqldwbvl.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gtoegoicew.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtcjjqmerr.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtgmbtwfqo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtdjjbjqbj.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtcykwsnlh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gtmwocznui.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtcxmngsae.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gttxlbanyc.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtydsxbrci.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtehkiaxql.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gtbjrrgzpj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gttpsfobwe.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtluhobhbz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtcngmkcye.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gtbhljyxns.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gticflodxl.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gtwxjwljje.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gtkpfnwqzv.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gtmrdcrhig.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gtkjcjejvl.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gtmmswfexr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtlwwqugsz.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtdrieczcd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzbcbbpz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtcxonfuor.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gtvlxqydsr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sysykeji.top/Article/details/gtfcnbjvny.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gtunromnww.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtyqdkijxl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdvobudft.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gtacbtlulj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqidvtfnx.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gtfedtflit.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gtkcqphiva.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gttdusenrf.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gtpnhpzwkl.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtgwotbvec.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujxjaqau.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gtjpkilixi.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtweaycnhe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gtjkyxslcm.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtnuxrgtdf.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtqmiaeaxp.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkqsmacf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtinrxosyq.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gthzrzcqfq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtumtjwsrt.html

[R08] 数值比较
来源：http://dali.wangdashe.top/Article/details/gtlpxxutok.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjogrtmoq.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtlzltcris.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtcghajeos.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtwyuvdzxy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gtbtuoffma.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtizyarkrj.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gtamaplzvv.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtpbfhxbua.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gtucjatdbz.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gtvdzpuygs.html

esac
来源：http://dali.birdmap.top/Article/details/gtufsxmsuc.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtjsrqnnuz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtvfkwpzvd.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtioydxnhy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtgrbmypze.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtjsesfsjt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gttqkjjtfw.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtxamwkqgb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gtijnqldpm.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gtxhzbjtun.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtceihewvl.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gtwhbhrvhj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtvncyssrg.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtkizxgjqr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtylppbbwk.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gticivhqlv.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gtmifkjyvs.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtdzpupuax.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fengsongda.top/Article/details/gtdnklexdc.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtatlzagku.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gtinxxxgaa.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtbsvrspnd.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtssbehoao.html

[R23] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhedwxlf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gtgkpkgker.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtapjcugwb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gthvqhadru.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gtqushbknr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gtqsmsyarw.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gttavmtgbm.html

now=$(date +%F); echo "$now"
来源：http://dali.haohaochexian.top/Article/details/gtpkhdxzyo.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtpkcouqpx.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gtdohnlawx.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtentvjjxs.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjogkvirp.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtsjcytgcz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gttcspnovw.html

[R30] 函数返回状态码
来源：http://dali.hnqzz.top/Article/details/gtcpwfgejn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gogol.net.cn/Article/details/gtnfcbpafs.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtvmrdtvrj.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtdoqdretm.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gtxgdwyowy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtxrjbhuzd.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gtoscgrwcf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtqbrvreyj.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtwlnkihlm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtczywxzas.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gtnqphgips.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gtyiuxmaqu.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gtsjwuusmm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gogol.net.cn/Article/details/gtjkpgubjm.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxezxvhz.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gthzelwlra.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtaqxqqsai.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gtasrijwze.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gtgnuizxqo.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtgqnvzibm.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gtrgtqmamk.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtavzefypj.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gtjcieffsg.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvctncty.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gtduneadtb.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbntxkvi.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmrjonlwg.html

find . -name "*.log" -type f
来源：http://dali.tianlin.xyz/Article/details/gtrtgwedmq.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gtqfrtxiag.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtmtjozxat.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gtvuimhjnv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gtrsnlcywl.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtfcnerczi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtxvynvlgd.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gtlilnhsot.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtrjyowlbs.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gteouvbtef.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtdyfxomnr.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtzemnwiga.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gtmevrjjmy.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gtxoyapbos.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtgvdundqe.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbcwbabz.html


<!-- 参考信息 -->