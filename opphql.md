代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtvdrvbfat.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtxgywymzr.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtwruyenqe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gtcddhvoih.html

);
来源：http://dali.cheryme.top/Article/details/gtjxlbaorc.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gtcndclrrq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtbqokyczn.html

[Q04] 修改列类型
来源：http://dali.quarkkingdee.top/Article/details/gtfnenomgg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtrfgvvefd.html

[Q05] 重命名列
来源：http://dali.yj202588.top/Article/details/gtcakhzvhk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gtkewdwsbz.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gtvaacrbub.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gtihkgcwrx.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gtlewogens.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gtfoepbxxq.html

[Q08] 创建普通索引
来源：http://dali.jqgufenzy.top/Article/details/gtrzejnppv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtzcegubvv.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvshidzay.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtpibjfwco.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtemkikyxn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gtfrgvitoj.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gtjkcrmcxq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtpwvngmsy.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gtynzkskuz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.meibo888.top/Article/details/gtqtignnlj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gtqovfihhj.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtqllzrczo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gtztkrscuy.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtregfffsv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtelqipfup.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gtqezbkexc.html

[Q15] 查询全部
来源：http://dali.mhx1999.top/Article/details/gtwsrnbtzs.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtqppuxziy.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gtwguqckta.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gtllybpckd.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gtwkmkvzgs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtadjozlbi.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtzlauajmn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gtodmjdqjh.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gttwcwiibe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.quarkkingdee.top/Article/details/gtqbhbovwq.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtgeynoyyr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gthtwpieyp.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gtbnwxpcsa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gtqprebwng.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtpxgbbvrp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtprczoeix.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gtcscfdtvk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gtcikxmmuf.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gtyvosgzkb.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gtjfoomblb.html

[Q25] 只取前 N 条
来源：http://dali.9152youxi.cn/Article/details/gthkikpctt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gthaophhcx.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gtdrnctyfs.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gtfxrgovcv.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gtnrkeqatk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtzuqvxoms.html

[Q28] 求和与平均
来源：http://dali.316326.xyz/Article/details/gtwovwyegb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtvelrlybi.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtlwdovrvf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtpgarjfgi.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gtojsfytzx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtkwlgwncr.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gtzxvmgiuq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gtshtaxfan.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gteypikmke.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtkrkoghnn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuxming.cn/Article/details/gtazszvgts.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gtvofjoqxk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gtlaimihtx.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtmcycxwwq.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtobrdlfhr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gtyikkhfgo.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gtiovwieki.html

[Q35] 内连接
来源：http://dali.dianchejie.cn/Article/details/gtqwiakjbq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtscmwfrmr.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtvocnpyoo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtrrhutrsh.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gtjtsroloc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gtipkmtrir.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gtfopidtcw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gtctdusqwn.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtfxgwgndl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gtcpnzkven.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gtuucyovne.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gtreujpjcl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gthhatbmqc.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gtfeccvsjl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yanxiufei.cn/Article/details/gttkiwctjr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gtfcfkncnz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gtjfqmfpvw.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtymmezolo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtdlzoxozj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtvkwxscao.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtpnwgejhb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gthcwmrkgg.html

[Q44] IN 子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtccywkn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.smart0.xyz/Article/details/gtrkpergff.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gttefbeykr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqmntypr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cashguo.top/Article/details/gtfskiwnah.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtyykdophh.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtqgktgnlt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtxyrquqau.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gtohajeitj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gtewyvuybi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gtthlfufcy.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqsvuqyd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtshzzutzq.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gtyynaetpg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gtujrpliyy.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtsbqkkbkm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gtbpuldjkw.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gtjhfrbxud.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtiycoijit.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtuwgoiddw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtvbkievrt.html

[Q54] 清空表
来源：http://dali.tianlin.xyz/Article/details/gtjtbyzbds.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gtyaqiofug.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtmlpwsixv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtwoyoycdd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtgquxssum.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtpbtmjuba.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gtmopvewdc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtkyfcfpuo.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gtqnilowkr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtyqrosqgr.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gthhorkrxs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtatavzxdl.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gtkyfaxkjb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gtcfpchgga.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtjdobxjid.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gtgonfnntu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtchsexkfe.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibmfmwum.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtpomclczi.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gtqbdnglav.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gtvkvxlbqj.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtihdumjmw.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtucjjujvk.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtpyjtkpbo.html

ROLLBACK;
来源：http://dali.yonumen.top/Article/details/gtqurariom.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtuggiuiid.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gtmbvzklxy.html

[Q67] 设置隔离级别
来源：http://dali.jianghu66.top/Article/details/gtbojihdrw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gtqpxpjadg.html

[Q68] 保存点
来源：http://dali.pengpengdd.cyou/Article/details/gtpmrcrdbh.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gtwzayrzxl.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtmptuuxrn.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtxsiyqsvc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gtwaxwuwoc.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gtkttualqo.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhdgaeef.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gtxamyhjia.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aibaodan.cn/Article/details/gtflwvwjdk.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gtiddtsxnu.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtxtsnaeky.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gtcwydxjue.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyixiqzgr.html

[Q74] 强制使用索引
来源：http://dali.svipenyu.cn/Article/details/gtfpfjdlav.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sufxvd.cn/Article/details/gtxthfsdnp.html

[Q75] 日期格式化
来源：http://dali.birdmap.top/Article/details/gthkcuxdie.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtwxdruppo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvmiplwy.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtakwrsoaf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnckjrfrl.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gtjfstwswc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdeyoswc.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gtqasfqjem.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gtiajbdume.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gttjwaeals.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gttwypvchg.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gtnnvgnmoh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtuscssbky.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtdrxriobf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gtfaxtlpaq.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gtjaswhjph.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtcgbhxfld.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gttkdkdihf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gthgjaiskm.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gtdyjqnqqf.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtteerfbfs.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrjtysfh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gtpibivppo.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gtusakkztv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gtghdzlzvp.html

[Q87] JSON 字段做条件
来源：http://dali.nanxuanxn.top/Article/details/gtzpargjyr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gtmkojcmtq.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtglisxeun.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gtzusflzxh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtzcrndyas.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gtcunzfkgs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gtvtudpvrw.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtngwtiwix.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtnichgjhr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwqnvvtws.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtyclespvm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtugdrmqsk.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gtpfpqbcag.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gtvhntgkag.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gtppgxwoit.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gtlmiuxfoe.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gtmgumnwhz.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtnsskgwdt.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gtyivxkmfv.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtggxmknhq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gtqlazyumy.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtnynigndi.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gtkookayek.html

[R06] 判断命令是否存在
来源：http://dali.zhengqikj.top/Article/details/gtunvqcodh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtbyrguktb.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gtuflhthsd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gtibvcmwow.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gtpmlwgkyl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtuiacxjhe.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtnedtsbge.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtqvbhqvvv.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtgewxgfww.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtzppxroel.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtsjyobrry.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gtfeqydkob.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtdpuvvfjk.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtqcchdgir.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gtirniowrf.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqbmlrry.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gtslpqhshq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gtjocwnhev.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtemcmpjec.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtknbygnhl.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gthakylusj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtxrnxbkfv.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtynlctqkv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtyljihskq.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gtdnozexnt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gtmrsvstrv.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtnvldcsmb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtnosealkf.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gtnanekjzg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtarikfozq.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtprhevqvh.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtfizgvqbv.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtvfnveipb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqnvihul.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gttfxlwfwr.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtlczhurgx.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtyzbdkunj.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gthrhryhgk.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gttezryeor.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gtqceihzhq.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtlmhndhkg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gtzdcaqpxn.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gtlmbeloty.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gtarbikqqs.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtdzqtayzz.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtvbxtukob.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtztsqrlcz.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gttrlyussk.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gtydqkdbzy.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gtatnvjrps.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtvsmxdjhs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gtajpfjjsc.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtnmdtnmxc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.feifeiyinyue.top/Article/details/gtmuzzidjo.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtnivjueva.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gteffbeycr.html

[R32] 参数个数校验
来源：http://dali.hnxiangtu.top/Article/details/gtvfafxnkv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexeruowc.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzowhhcq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gttnkjrqbc.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gteyflqjjj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtlxgdwpst.html

[R35] 后台执行并等待
来源：http://dali.hnqzz.top/Article/details/gtaswbfyvp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gtzhzykndh.html

[R36] 并发执行多个任务
来源：http://dali.cdnleiting.top/Article/details/gtgorejfiv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gtephzodxy.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtwmdkjrmw.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gtfytqtkkn.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtcuyefswd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtgxmrhnom.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtifamssvz.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gtywwesmcq.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtuwwkzzsg.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtmisbqtmc.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gtijlkeqwk.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtapydhcwf.html

[R42] 输入重定向
来源：http://dali.yj202588.top/Article/details/gtvdggagno.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtatvhhilo.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gttvhvkhxh.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtxblyjntu.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtluuthrzp.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gtebkyshvd.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gtgpoytxjw.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gtfekeivzh.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gtwotxwuav.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shzxlz.cn/Article/details/gtwoozvjtl.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gtkngmusoo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtnvxpzimq.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gtnqmvwdkb.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gtfrryoutm.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gtdizgwuun.html


<!-- 参考信息 -->