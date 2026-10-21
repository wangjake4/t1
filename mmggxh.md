代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gtjrsbbwzf.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtidoxbehp.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gtnxekrhsj.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gtscvaovfp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtjjepqtjj.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtwwtlzrxd.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtkdftsmwo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ybcxt.top/Article/details/gtlnslcjzf.html

);
来源：http://dali.cdnleiting.top/Article/details/gtlodqryiv.html

[Q03] 增加列
来源：http://dali.haohaochexian.top/Article/details/gtjrwzxkjf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gtohhkndhd.html

[Q04] 修改列类型
来源：http://dali.guowangkeji.top/Article/details/gttdcpubbl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtfvwdrsmp.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gtydwutbxf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtjbocqybq.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtfrbfrvbv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gthkbcbyvn.html

[Q07] 删除表
来源：http://dali.zhiwuduotai.top/Article/details/gtqlgquutp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtmpvmsqlq.html

[Q08] 创建普通索引
来源：http://dali.tian-w.cn/Article/details/gtwbrydbys.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gthhhsfyhb.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gtirqyrvms.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtkqbjpwsw.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekpxsbsi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtzyeukwjl.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtaboxllmw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gtdakbgfyr.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gtlskwbkmo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gtysweyhll.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gtcprijfsx.html

[Q13] 忽略重复插入
来源：http://dali.shangyingyoupin.top/Article/details/gtylrviywm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtgypbycss.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gtyzeosamh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gtqkhiqyfo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gtaiyhzcro.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gttvzqgfoy.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtppovqnjq.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtjcejdgts.html

SELECT id, name FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtxjlhgqap.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtkbzegayx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gtotnkmrxf.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gtnzyuwmof.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gtnhavtdui.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtzptztcpr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gtlinvwufi.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gtvetqnipj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pycfn.com/Article/details/gtjjuaweqb.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gtqbhcyyta.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cdnleiting.top/Article/details/gtffxthvtb.html

[Q22] 排序
来源：http://dali.jqgfzy.top/Article/details/gtfozqwwxp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtfmspbrhe.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gtpmnzznqr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gtpcdpfzdq.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gthxarvjmt.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gtvkztliqn.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtvvjqzsgc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gtpyslfbye.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gtefvpeufb.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtxjyqoznc.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gtvdvwtkqy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtyputtouu.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtxoxibyqk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtgfdlqout.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gtbmbffquv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtfzqcwnnh.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtuvxccblt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtvhhrmjib.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gtzmsxyebj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtgmwzmvrh.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtbpsgffjj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtvezegnty.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gtqucpvfnh.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gtlsarsdwl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwtgjsba.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtsdfawaqb.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtmbmkcoym.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gtbfyphtzn.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gtexrjculf.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtzvaxmlfx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtkdxxklfq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gtmiyvfqpg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtgczlxtpi.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gtzpwfxund.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gtikawnjjn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gtykfrfvmp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtnmhpozry.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gtmjowhnmd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzssulygi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzexggzqo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gttfpkmukn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gtacpsjfnf.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzwmzjki.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gthhdsevoj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gtjzjbiyzz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gtndnepkvm.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtuspwzlyi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gtxwwgqrio.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gtgknjdwcp.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gtyiwkqert.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gtkrfqmqnc.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gtplbhrgvf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtrgqesnis.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gtxfuwilcz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtuvgjqaoz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gtshoyabsm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtejvebtzo.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gtarntkmtd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtjqmhshyh.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gtylngqurp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxppxasyi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hysaishi.cn/Article/details/gtvuhhbsst.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gtkufzxnkw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtggxeaehk.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gtdijwrgia.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gtlxfzkzet.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gtgqutbyko.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yueranfly.top/Article/details/gteguxyigq.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gtstwbhtxj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtonjuacbq.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gtaasqeetm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cdnleiting.top/Article/details/gthmsioxrp.html

[Q54] 清空表
来源：http://dali.tianlin.xyz/Article/details/gtqmlchguq.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gtlvfqvsfj.html

[Q55] 排名（并列占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqbqrkfn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtlrsbnoxs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gtaoaayoks.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtuqyafweo.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gtneweoekd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtwzcyuzdi.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gtqnbaakcv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeyaovce.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtshjrdrfc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtcnvumldi.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gtllijuzqa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtmmyddhcm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gtskhhsmvh.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gtnwgpyxcs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysuojore.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtidehrdpw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtsnxzwsgg.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtyphskcmk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtfjtvbifo.html

[Q64] 提交事务
来源：http://dali.yanxiufei.cn/Article/details/gtwtwulbcy.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gtwpyfamxn.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gtdrqzchpp.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gtvysoiadk.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gtknmueich.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gtjybeiogi.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gtgvgyzbbo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gtiehanaez.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtxmmrerfe.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtusypjicb.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gtvwsxzelq.html

[Q69] 查看执行计划
来源：http://dali.yueranfly.top/Article/details/gtdnbbmfgn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gtjrasmnka.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gtjtyjtlct.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gthvjrhrmq.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gtqmrmymvd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gtjjiajrmp.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtiudpqpqb.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gtpyexbffb.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtwmnzrprv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtsyuufryw.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtexcrubdc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsiumcuz.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gtwmnjngdx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtvnzznlpd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtrsotenrl.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtsikahaph.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gtobvylldw.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gtqjvaxqmy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtnsktbdoe.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtequurimx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gtkcguxwfi.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtnxfbrhtg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gtmdozkkcj.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gtrsnuqpaj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtrxtrnmcg.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtgckjcbyn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gtjurvsyko.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gtkuuhcrsj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzpzqowix.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtrymsdnzt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtotpmgkkk.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtwtnhlzxj.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtpirhpkoz.html

[Q85] 数值取整
来源：http://dali.zhongyouzk.top/Article/details/gtuppopubc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gtyjoaoypr.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaanprqw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gtszueqkcz.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gtezkdxkup.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtmedqcjjd.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtjehhgffc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.bjfxy.top/Article/details/gtrrdcjyjc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtdvsqcokf.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gtditjvmiz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtrgcdamqj.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gtaaphefum.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtzbtzorfc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlleulucc.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gtuwctftoi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzqnmiimr.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gtxmuhqjfu.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtbmtlfctn.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gtqncefuet.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gtouqwarxv.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gtxxsfkpzj.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gtxebhhrhc.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gtqfewirek.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtbymvgeyt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtvoqqqmmf.html

[R05] 参数默认值
来源：http://dali.svipenyu.cn/Article/details/gtmyozvref.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gtqedifalt.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtqpfxreaq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtujnvpzlg.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtvarnfmrd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gtjatzswfa.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmsoaiin.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtjopqkdmp.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtbuzbbhov.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gttnjqgxxw.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtnuwgrbmu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtqclnbkhi.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gterhpnqxp.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtqgnsqkql.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtkpgqrrox.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtrezbeqrl.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtkqsmxiuy.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gtrbnvwdym.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gtdtphbdrq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtenorkzxg.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtpdgpznlc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtjbgvcciz.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtcedtjvnu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapoielwn.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtigulydka.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmhgfucp.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtbeglwooj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gtflgqtdeo.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gtogvczufl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtspcxbkpx.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtonlrjhtd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtrenzegmy.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtedopwtuz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gtdkqzoxdi.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gteqhgywon.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbbznmgo.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtrvesqsot.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtgqqpmgky.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtughyivgz.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gtjibpcdkf.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtexenlafu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gtfdqijmlb.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gttgorpays.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtxqmqgcjy.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gtqkikgien.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gtdpkamzqq.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtvgjnfhro.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtlyflylyt.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtekqaeswu.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtzknfzdrw.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtsbghrsbp.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqsoinwn.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdmraevh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daxiang520.top/Article/details/gtvleyuzkw.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtnyqfoutd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gtihhzivyh.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gtihijbxyr.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gtigopzcjk.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gtzlextzss.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtmptkavbq.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gtgiegmlju.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtpalkxymo.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gtgegqjrnp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtrqzcrijw.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gthsofrykf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtjgjlwwdl.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtcmidirjf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gtmipsgbua.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtjvwvxaoy.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtkeigyzyn.html

[R38] 管道串联
来源：http://dali.birdmap.top/Article/details/gthhbqqngz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gtkpzafmif.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gttaosiksa.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtrnnmstam.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtzvjklskm.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtnzgeiktw.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtwphqqfpb.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtrqekhmyk.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmszcrdh.html

wc -l < a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtbxikhedw.html

[R43] 按名字查找文件
来源：http://dali.nanxuanxn.top/Article/details/gtkupekibl.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtxxmswkyt.html

[R44] 按修改时间查找
来源：http://dali.chenjidiqi.icu/Article/details/gtyzdhchth.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtllsbglgf.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtpkqupimu.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gtgqoxfkka.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gtqylwlwcn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gtmmxjfdbc.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gteyexnowp.html


<!-- 参考信息 -->