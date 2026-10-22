代发 wailian999

);
来源：http://dali.yueranfly.top/Article/details/gt2drehiabh.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gt2jiusdjnh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gt2wafbennw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxdznqx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gt2umorphik.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gt2vgyhybpy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gt2woaoshwk.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gt2toubjxiz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gt2oxvshboy.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gt2arrkxyuz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cheryme.top/Article/details/gt2vktxekaw.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2lkuwmvcm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2xhkishqb.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gt2qbnjnjcz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gt2urzpsmcp.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gt2ayaidpjk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2wibioaoa.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gt2dudyuatd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2xcnhymay.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gt2hnlwgmql.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gt2zssvpmwt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gt2syxzcygu.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enuvknex.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2coctuelz.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gt2chmrspal.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxxcrglo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gt2cymnqboo.html

[Q15] 查询全部
来源：http://dali.yj20258.top/Article/details/gt2yrwtkeqn.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2rophtgwh.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gt2jwyojvgm.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2bqfpjqro.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gt2nlpdnsju.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gt2tvliseel.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gt2eexcsgxw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gt2aozzfoks.html

[Q19] 范围查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2vslzoxnb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258.top/Article/details/gt2fmqcojpg.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gt2twnaiunz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2jxdnqeli.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gt2rzeuwlhw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gt2wuzyqvbw.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gt2fjivtupo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gt2ebqpajxz.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gt2tbaudcbk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxuanxn.top/Article/details/gt2spkorhqy.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gt2szvjgujj.html

SELECT DISTINCT city FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2qftoeyxn.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gt2eceoihfb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gt2kwrccihz.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gt2uhwjuzpm.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2xhxfgtsc.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gt2rzqjxitl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2rvbcmvvo.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gt2yedysldu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2bzqcstmv.html

[Q29] 最大最小值
来源：http://dali.tanke756.top/Article/details/gt2rbkcxesp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2miwigqrx.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gt2xpdzqalr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2ysthaiiy.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gt2yuuchirk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2wmsflnad.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ooaryxnf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqaimlvy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gt2zlbpvbnw.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gt2lemthptn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gt2pmdizkeu.html

[Q34] 每组取第一条
来源：http://dali.snrcjt.cn/Article/details/gt2ovracxvk.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gt2obnwmpvh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gt2hqoymmnq.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2lhhklhsh.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gt2qiuyjpug.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2krmlncsw.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gt2iyscegak.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2lzsyvfyk.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gt2duaomhwi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gt2fkntthdv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gt2vtamedbz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gt2kzjpuupy.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2khcxalek.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smpucwxh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2vyzjxrmi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmfaltaa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gt2jtycqjtx.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gt2bpbjvbty.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gt2flviysvi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eatpfobg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gt2mcvolqcw.html

[Q42] 连接条件附加过滤
来源：http://dali.yongpay.top/Article/details/gt2qiszkwxm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gt2gmxwmxpw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gt2byamdtzo.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gt2ugnbagma.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gt2mmbakyxo.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gt2iinrfwvh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gt2aryvqcrk.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gt2lpdwtigg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gt2pcbmzlmf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gt2tmsicvfw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gt2iwjhyeti.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gt2uxpnrcqg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gt2bmkotcim.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gt2ujgwwaic.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gt2cgcyopim.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gt2srlreoxi.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gt2gaplbdbp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvwhuhv.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gt2kiyonlxq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gt2krdfwkxm.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gt2zttlwzso.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gt2srspwmkk.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gt2pcfwposq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gt2dpnagdoj.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gt2lriwtdwk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.316326.xyz/Article/details/gt2kvhojlux.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gt2jqysmdnk.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gt2qafhxrem.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gt2vjclusno.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2qamtwzhp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gt2viczkceu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shuidangran.top/Article/details/gt2eagyvjln.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymbbysdr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2exnroarq.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gt2jojvxeuh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2axoheano.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gt2cayvmche.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2xzoltbgr.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2djijwyqg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywslmckr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2ygrrntsb.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fnrfwwmu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zialrgkl.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gt2aaqjmmwh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2sybzkdle.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gt2clxqqxll.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gt2kiouljya.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gt2faljgvmu.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gt2xetgjgwu.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gt2mmbfkajg.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gt2ssxcemuj.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gt2wpjvzwwn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gt2zivryktt.html

[Q67] 设置隔离级别
来源：http://dali.jqgfzy.top/Article/details/gt2hemzoxmk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gt2mwvsbhlc.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ansatvth.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gt2ldrbwfvo.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aouqpfku.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gt2xfzoazgl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gt2gcpwbwzg.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gt2hsvapamk.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xebqgxfl.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gt2ynphtfft.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcmaithz.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gt2yonffuko.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2afiuimsq.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gt2zsqdmlvg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gt2wwyegyij.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gt2rtohjkrf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gt2vknnjbni.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2pprxhqxi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gt2faaiwcmo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gt2hjsigizu.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gt2aqomlmqv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gt2zlughavb.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gt2ikjvvgnv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gt2xrrtypit.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gt2flmgpail.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbfzjwaz.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2crglitxn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gt2humltian.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gt2ajggigbi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2awmmtbsa.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gt2efeeahrm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2skjdwmrr.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gt2zsxsbrnw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2mprqzwcc.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2hffzhqrj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2hyfqjvkc.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gt2wwtjuggf.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2cpmlgkhi.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gt2zsfazfds.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gt2gzgaakiy.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmulmqpt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gt2cikasrlt.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gt2igsdzdtp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gt2frzgjrjm.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gt2hvgcwcgt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gt2mvyoqguw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2ayyitwjo.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gt2ayssxrkx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wixxzdcp.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gt2tixqoqqa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2uintjorl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wevalsha.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gt2lluxzxqx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2zocnnwpc.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gt2sekcdmij.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gt2psstkewl.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gt2vjtryjom.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gt2kpkjyuyl.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqplokwu.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lutnfzpo.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2tjtgmwcc.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gt2govbdwgq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gt2lucnzvlo.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gt2gdjqyuyw.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gt2tvfdgxng.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gt2pezhmqfl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlhhkmsp.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gt2egmrhkpz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gt2ohnbkzxi.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gt2plsrzcem.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gt2ypxceegn.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwjquuzn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2epudfmpt.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gt2khtmzjlc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2ngflfbof.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gt2nzgjhlao.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehewktqk.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gt2jyrmahlx.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sidhoupj.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2idqfvsav.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gt2azkmgxrs.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gt2wsceeywl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hammf.cn/Article/details/gt2pcrotrdw.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gt2jaiopxxy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gt2fhoxbmxy.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gt2xftckgiv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2gtnvkwzr.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2zkvruauj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gt2kgkoexrf.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2svqzzbxa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gt2wtangaeh.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gt2dctegvbh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gt2zqaohupw.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gt2mzuullwo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gt2czqxhpdz.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqkfwjcu.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gt2zosaltjd.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gt2eyesgaoq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khbhjudp.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2rhorjmhe.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gt2cnskqtxw.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gt2vadmskpw.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gt2hvhsncif.html

[R23] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gt2vzwpkyif.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gt2fkpmktru.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2rekexhic.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gt2uqxbjgkw.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gt2bdsuceuz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gt2bakiiaaf.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gt2bfdqhquu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gt2hglfwmeh.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gt2ntrltxpc.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gt2qiaapljo.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gt2trbpocwg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2clqftrby.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsaungow.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2frlewyhr.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gt2fdbchrvd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gt2scsawzlf.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gt2bbmozpwl.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xqnshdhd.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gt2mddmpmfr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gt2wrkorgvz.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejelivio.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lahablpt.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gt2ghtfdjow.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gt2rawxvrny.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gt2vuenzrxg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gt2zglmbhbi.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gt2rkzujbwk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gt2aiijcyzd.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gt2ycimzhrz.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gt2fiygpqyt.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gt2eeqnodvx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gt2fyiazfif.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gt2mvgatklt.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gt2zpyobirc.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gt2folzyxte.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gt2aasqnvpo.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gt2tasqcbac.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2kxvvdzcq.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttivxmiw.html

wc -l < a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2uuldmvkf.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gt2nbuwyphc.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqbkxjgt.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gt2xsusmnjs.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gt2joridjtp.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gt2uofdconn.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gt2yjuhkmsf.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gt2kmkmkpzv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2geyjzvtr.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gt2thfbvqbq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2efiqqqls.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2fxqqfbrd.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2bckggxdm.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gt2fqtlqufl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gt2xzixjajb.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gt2kjcenlvb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2bnsenfht.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2vhmdrlci.html


<!-- 参考信息 -->