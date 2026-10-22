代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gtfjdguwxo.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gtpkbzzsss.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj202588.top/Article/details/gtzqnyygrt.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gttgvckcqz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gttxeligeh.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gtasxonvff.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gtdjkpodoa.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gthtfghzsx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtiwvdfxta.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtugekpzql.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gthpfkzlpl.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gtmgjmcwpm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtqmhvfnxk.html

[Q11] 一次插入多行
来源：http://dali.iojbl.cn/Article/details/gtfqcozzao.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtmywvxflp.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtfkbyvytd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zdqjudy.top/Article/details/gtzgrxtcvp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gtjprrwivr.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gtjmshymyg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gtqitmpxsj.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtgziidjvd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gtcavvjzud.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gtpbdpetkb.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtwvwochyn.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gtfpvjqfzx.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gtefncqfxm.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdmbsgsz.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gtqmlabyqu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtamyqujdg.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gtqmhspflj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtcyjootec.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gtasqflfwx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gtmmjkjnzb.html

[Q20] IN 列表
来源：http://dali.jinqigfzy.top/Article/details/gttqtxkbpl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtllyzurqe.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gtirgzypxn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtnpyucdmm.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gtnthoctgx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gtjcuygqbf.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gthzhxbkek.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdewxrydw.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gtdkgkifuh.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtuqumwjkc.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gtgyoiinea.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtbsrsmlry.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gtfctqlgza.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtwkefyvpy.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gtbyvdqbms.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gtghlxshcd.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gtcekcsixo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtsifufioj.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gtavwzcros.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtxlbyyofl.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqbkuyfp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtdzccpzfu.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtmgumdwgg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gtpysqoyxs.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtibpfihqq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtvuymnuru.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gtomnfgack.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gtkgwqkgep.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gtzysiwypy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gteqoelkkv.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtytgcsjgj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gtfmgesgsq.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtayjbgxnj.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtxxehzgrn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtgbstqbut.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gtlyhndrxr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtzvfhnijl.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtaabmssmk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtuzajcpjr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gttaesenin.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtffbiorit.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gtslzsrdos.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gtsldwaona.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yongpay.top/Article/details/gtxzekmnpm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gtjzbbjmrj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtazkqqxhe.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gtwhzjatuy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gtlomrhvza.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gtdyljhufr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtlsfoascp.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gtvpyltoir.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gtqmargvel.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daria6918.cn/Article/details/gtiychhiww.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gtmsdkogrg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gtoljluixz.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtuthzdrua.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtxhsraiib.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gtigyurzaq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtlagmupyt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gttlrkpzed.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtarvxdpjp.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtwkmcycfc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gtsjexjldr.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gtheknffmq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtpmjcfzqy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gtuxtocbjd.html

[Q49] 更新单行
来源：http://dali.jqgufenzy.top/Article/details/gtyeodixhp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtpsjvhwce.html

[Q50] 批量更新
来源：http://dali.havefunace.top/Article/details/gtxaicinbd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtcqnzbcra.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtylfxyvfu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gttagrzcte.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gtzhupdsgi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtpqbyytvq.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrkulfsc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtcclemmza.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtrpmmdost.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtldyiwpub.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gtlktoddij.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtbdrlwesk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gtuhxwcmck.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtnyzjcwhc.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtdmbkhtqb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtmwsbcewy.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtgjsazmjp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlypluhcu.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gtxnaqwdpl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtsivsppqr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gtxkaqzdth.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gtuyphypvk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtokgfgmro.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtizprpkpc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtvalyeznb.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gtjqtlixij.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gthrtiwuog.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gtjpystqvy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbrdctcy.html

[Q64] 提交事务
来源：http://dali.hywenlv.cn/Article/details/gtsjumlnvy.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gtowmduswj.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvrxkodb.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gtiinpkbxy.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gtqwwhqtib.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gttdzxofun.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gtdedbmfkf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtdtdymyal.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiygsorfy.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtnqmwpzyk.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtudcfxzea.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdncpkmq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtdybirxxr.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gtabwttmje.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gtobxlkque.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gtrmjcxmwc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtkjsoflcd.html

[Q72] 查看索引
来源：http://dali.yvedp.cn/Article/details/gtoxklvdix.html

SHOW INDEX FROM users;
来源：http://dali.c1oappe.top/Article/details/gtswqhnkbi.html

[Q73] 查看表状态
来源：http://dali.wangshuangyany.cn/Article/details/gtbgosrqip.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gthzscgwmx.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gtohqjcdgt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtmifwcvze.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtnjtupsgn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtzgnhrejb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daria6918.cn/Article/details/gtxnjvhqqh.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gtbsebwryy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.redwolf501.top/Article/details/gtwtcctxyq.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gthwajrosv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gthjqcxgda.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gtjbjjiqwa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gteiwcutdt.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtwelnsgqc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gtrlbjgeia.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gtrdqsegrh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.andypj.xyz/Article/details/gttumyygnb.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtneavrhya.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gtvqbbbhjd.html

[Q82] 字符长度与字节长度
来源：http://dali.dashuyun.cn/Article/details/gtotxwqnbn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtdxdbypyr.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtjthhcnrv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtjsixjsnq.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gtqlugexnt.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyvrhgqt.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gtlwtorkhe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gtlwmybuhd.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtymfwyxwe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtrspirtdd.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258.top/Article/details/gtchxfcfne.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yangfankeji.com/Article/details/gtndmrfdgm.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtbtfybrfk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gtytnzxyai.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtudhrmfva.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gtisludwiw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtfddxokhy.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gthkapbfsz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvynucxnu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkdviqhvo.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gtguldsdnm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbxaffbmh.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gtwxgmpabq.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gtsccyldgr.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtivvfbtfa.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtcavdflqi.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gtjtbccvxs.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gtjqlzgydy.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtfqtkhkkg.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gtjxpwhjgq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtkronooxp.html

[R05] 参数默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtjvsbwwpt.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gtdhewgywk.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gtjqhwxyan.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtrwwelmml.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gtoxnyzime.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtvmlynksd.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtriivprlx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtkxrcccpr.html

[R09] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gtyptyjiiw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtptnxqsjb.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gttzwsncgu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtcmlodbgj.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtrkdaujaz.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtendnojmf.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtmynlwfhb.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gtgvkrcxmt.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtvesilyqg.html

esac
来源：http://dali.9152youxi.cn/Article/details/gtqqzampsb.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzldgfre.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gtbrjxydez.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtkmcwmwdp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtwynhtlch.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gtdcnliieb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtmhpprnjw.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtkkxnrrmi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtksjqavzo.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gtvlfzcvcx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtfonnlizg.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gtscnrahml.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gtxuwobrho.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtstvwuvwn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtkpgykonc.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtdzerrkvg.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjnphddc.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gtuydmrkla.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtzngilgso.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtqjtkmbtv.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtuqghftkh.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gtrkwabxdc.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gtnhipicvd.html

[R23] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzlobqho.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnqzz.top/Article/details/gtlynknhtl.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtperbzxfg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtufvclznt.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gtxzilskgh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtqzxxtfnx.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtzwrcqzhp.html

now=$(date +%F); echo "$now"
来源：http://dali.cqqwz.cn/Article/details/gteiubffmb.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gtysnxduby.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtlqfccjwj.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gtfhgawpbk.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gtkskvwnzf.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttattfinb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtakcfhsyj.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtxvsemmbs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gtejwibbzt.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaodqovrj.html

f() { local x=1; echo "$x"; }
来源：http://dali.sysykeji.top/Article/details/gtecpexzrb.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtgmhcblet.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtnljeitzo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtyogbmsbo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gtpetnpath.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gtrikfbkip.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtyhfwfrvi.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gteagfzpwd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtgvjutxjy.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gtrifspqmv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtpqossytl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gtpckjxbax.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gtjiaymznf.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gtvtqmrcxe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtmlwxtzjj.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gteigitcju.html

cmd > out.log 2>&1
来源：http://dali.cucudq.cn/Article/details/gtqdpfnhyz.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gttnabjvuy.html

echo "log" >> out.log
来源：http://dali.meibo888.top/Article/details/gtnfdzymtw.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtzypsbqzg.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtpgawyjxq.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gtwqsbpsvv.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gtnyaxrrti.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtksqrnrzh.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gtlhyuuets.html

[R44] 按修改时间查找
来源：http://dali.nanxinkj.top/Article/details/gtcwbiefkc.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gtmdtkvhqd.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtczwzaowl.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gtpakkwwfl.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gttatfbfdu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtyushepln.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gtwqilxsrx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gtamqqrcae.html

[R48] awk 取指定列
来源：http://dali.sufxvd.cn/Article/details/gtmcnflpfg.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gtwbyludwg.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gtumvlxahm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gtobghkpap.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gtttzihxmx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtuptnbgzf.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gtcvtekzsy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyfpberh.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gtviidvyri.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gtlopumuir.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtvuqqjumi.html


<!-- 参考信息 -->