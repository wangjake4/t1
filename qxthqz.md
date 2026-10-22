代发 wailian999

);
来源：http://dali.havefunace.top/Article/details/gtgvmwcxlq.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gtbulambxj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtunvkjbyj.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtkpkujeeq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gtcxxbqlbs.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gtyohskwvb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gtrhzqonvk.html

[Q06] 删除列
来源：http://dali.yuanzhike.top/Article/details/gtywlywige.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gtngekokys.html

[Q07] 删除表
来源：http://dali.hnxiangtu.top/Article/details/gtssjahjio.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258.top/Article/details/gtnrmlygmg.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gtukzbgfzp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtvsatypql.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwylccqv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwjdqwhd.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gtqaisixov.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtlsxmopfz.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gtifbnbrbh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtsqfzhyws.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtkewwalbk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gtevwnqoyh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gtoggiurju.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gttcelbvhj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.316326.xyz/Article/details/gtejolkhys.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtodfhwsav.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gtvrvrogeu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gtpplxyryn.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkifgeeav.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gthxufwamc.html

[Q16] 查询指定列
来源：http://dali.zhongyouzk.top/Article/details/gtavjlrhew.html

SELECT id, name FROM users;
来源：http://dali.mhx1999.top/Article/details/gtkohtwexx.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gtpeaxyjii.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtmfoznxkn.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gtostpgeld.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gtlwfmdpkh.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gtrffzspqa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ehwqpu.com/Article/details/gthrzoviyq.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gtwzdzpusc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gtwbgfeqku.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gtybmnlzpc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtefbrsneb.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gtwoyqlssg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gtqpvjmfle.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gtsepyrbiv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gtrozofcmx.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gtryimdclw.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gtjcuznosu.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtezwnplir.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtbuqkjybq.html

[Q26] 计数
来源：http://dali.redwolf501.top/Article/details/gtwiwqywgf.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtfrbqrxwz.html

[Q27] 条件计数
来源：http://dali.hnxiangtu.top/Article/details/gtyvgjxrdq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbejytqry.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gtapumofgl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gttrvldwog.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwrbfwcl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtuspmzxht.html

[Q30] 分组统计
来源：http://dali.dashuyun.cn/Article/details/gtclbwudpm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtsnmgwhog.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtpkhmwiut.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gtmepkmkco.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtawmccghz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtbgguygop.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gtiwibmoxp.html

[Q33] 多列分组
来源：http://dali.xziqi.cn/Article/details/gtndyfmtkw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtpaqvwkcv.html

[Q34] 每组取第一条
来源：http://dali.jinqigfzy.top/Article/details/gtlgcaxton.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtrecsaovt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gtvmyfjxlt.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtosipdtgq.html

[Q35] 内连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxslavrcx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtyeegkksm.html

[Q36] 左连接
来源：http://dali.nanxinkj.top/Article/details/gtdiymgknr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtostvihln.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtdmbppwih.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gtauoicbxl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gtjqctgnqo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtbhkiqomo.html

[Q39] 自连接（查上下级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxzabmje.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gtegxakptc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gtsasjxucg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gtadmrgmsl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmchlyhbp.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gtliowcdae.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gtdqnhlcjw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gtfrsfhfiu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtvtleiigu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gtptdqxjov.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxobfysml.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtpitmwove.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gtsaefqvom.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gtxsoizmzm.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gtvlgawaec.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gtwtialfqr.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gttevoojsg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gttyzmjygc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtbhhqgibq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtaddqkhgf.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gtrqfvxsbk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gtbtliwlgx.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gtqzbcqerf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jiagoushi.top/Article/details/gtdricitgl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gtswtcpqfi.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gtqaebpryh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtcfbvsrdg.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gtzvrkawsd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtnubrsbpo.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gtrqidlsqi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gtrpsdwoba.html

[Q52] 删除指定行
来源：http://dali.316326.xyz/Article/details/gtnnghobcy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtegzsxjtr.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtkautvjzq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gtfifultio.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtvpfrszeu.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gtcgzwqkud.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gttqupehii.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcbrmlvm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gtstvvkbgr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtmzdteqmk.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gtdlmhzwra.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gtafpzznot.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtpdwdqgzc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrenhraoi.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gtpzkhaene.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtruzcixwn.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtlfsoicfz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gtzlmpqsho.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtgbdefknl.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtlsvrkyxp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtlaynuqlw.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gtsukekkld.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtjfbyzpfb.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgudjgvf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtmxvztcto.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gtdrkjiiee.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvjnzjpq.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtqdshcxcz.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtrdklccze.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtddkacviq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtyfkaawgo.html

[Q67] 设置隔离级别
来源：http://dali.yanxiufei.cn/Article/details/gtpdkpgbef.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtldzlcvip.html

[Q68] 保存点
来源：http://dali.ivvv.top/Article/details/gtblbwgqad.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtepqqfncq.html

ROLLBACK TO sp1;
来源：http://dali.redwolf501.top/Article/details/gtcupbjbxg.html

[Q69] 查看执行计划
来源：http://dali.hfpthk.cn/Article/details/gtlduyidpv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gtuudjcxqv.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqbgahpa.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtvuuuravu.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gtnjjmyuvb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gtnuixnzhs.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gtvgjjcfow.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtgspcnhvp.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gtitjcpets.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmomjgxh.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gtxwfpaozx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gtiveskook.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtnrmqlmvo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtfzudpzcp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gtbjtfcvnz.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gteucyoojk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gtltjsodul.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gtwptcjgyf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gtexrtzcpt.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gttlxffiuj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtknsybacp.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtuczkzcmv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gtnnkwrfdw.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyypigfb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtlvrmuhxk.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtlqaevxui.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtmklhbexh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtrkwgpruv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtnrouesdt.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtkwizalbn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtxkjcrgms.html

[Q84] 去除首尾空格
来源：http://dali.wangshuangyany.cn/Article/details/gtgokfvpww.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtzoobnwjo.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gtkstkjafi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gttvtfepfd.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gtnejoqxaz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gtdjvnwzor.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gtgjfoteva.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqntgpml.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gtihbzzjtq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gtlwpyblkx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtacspmyge.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtmotfgles.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtwthwykwr.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gtphczxbfl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gtujhbriev.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdejcrgno.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtsvsjxdxj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtobetxboo.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gtnwttfzxk.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gtywzkqymr.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gthpwbwbfq.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtugtnykxi.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtvptyfmsg.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gtlmxaksxc.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gtvvyiovro.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtnqcshvlq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtqvpcwzsp.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtgqggnngn.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gtpxuilxzv.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtnwlsmaex.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtbjykyovq.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtesrjzwfo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gtrcutrizh.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gtlzkoosrj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtibwpawvi.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtknzonmxr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtyflvxugw.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gtdbictima.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtksjezbfu.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtdmqkwrsk.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtcsicrdks.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gtpqzvzysy.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtnrrradvz.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtvtsdzind.html

esac
来源：http://dali.xziqi.cn/Article/details/gtovbgbayo.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gtvzmualsu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gtqzijkenf.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gtcaeehmuu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtlfxyowln.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtztkxqedw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubcuvgyo.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtjafjeqve.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gtrfexbcpu.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gtukyirtvq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbgfunjn.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gtzagrntbr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtramejahz.html

[R18] 遍历数组
来源：http://dali.yj20258888.top/Article/details/gtwjiciwra.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gthwmxsvno.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtdghmepry.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gticxvbmmz.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtwkjozcqr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gtfxadgskh.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gtfufljdsm.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtybsoxtsg.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtvsgmkycs.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtdjdonwpq.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtfrqzigzb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gtmcaxeshy.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtkncunphz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtvlmlinyz.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gtirajxpzl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtwlxnwurr.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gthzwzdjkw.html

now=$(date +%F); echo "$now"
来源：http://dali.daria6918.cn/Article/details/gtedslmrqk.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gtbtkqkqwz.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtmapgkftz.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gtehsjcztg.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gtmtxkegkp.html

[R29] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqhabicy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgufenzy.top/Article/details/gtebzayybh.html

[R30] 函数返回状态码
来源：http://dali.jinqigfzy.top/Article/details/gtdfvqfmks.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gtauvlvyyw.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gtwtnznphd.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtcctvetac.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gthsqmdvmn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gteljkaqeg.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gtzwzmhagv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtufinfbvz.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtxfutjeqw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtcksoqmmj.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gtjmqfvhfk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtrajqifow.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gtdwrjzoyy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtlrbaklzw.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gtlihkkxsl.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gtxwkrlxun.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtkberykrj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gthtgenjtv.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gtulgmcsax.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gttjeatqdj.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gtrgjenlto.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gtrmfeqpom.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gtcwzktrws.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtqvztsjpn.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gtsipjzvfq.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtddeksegl.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gtbxqdsjki.html

find . -name "*.log" -type f
来源：http://dali.tianlin.xyz/Article/details/gteleiffcp.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtxrldphbp.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gtbvoclwba.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gtvjfejvbj.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtoibhzrbe.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gtzoreccsh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtcelyopqg.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gtmkaxoegd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtikvqwepf.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gtqywjwtvs.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gtxlldmsxh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gtashtegfj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtfneyhica.html

[R50] awk 求和
来源：http://dali.aizwys.cn/Article/details/gtxcludgis.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtlnoxkvar.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkafcmfxx.html


<!-- 参考信息 -->