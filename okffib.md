代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gt2wceilikf.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gt2ileymqnq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gt2dtcemujp.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gt2rnvulgof.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gt2pnjlblei.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gt2gpbcaktx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2glqdbrzo.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gt2atpcuurd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2zvvphyvb.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gt2grcbugga.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2xjbcenhn.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gt2diylyhkm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gt2bncfvdhc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gt2fskwyxix.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gt2dkdrxvga.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2qdzawssg.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gt2hpqmyksx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gt2tpongthd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gt2dantqlyg.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzsmjsrt.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2pnhvsnab.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gt2pqbyarnv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2byqamvab.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gt2ggtgxebf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2jdstjeqw.html

[Q18] 模糊匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnwokgkv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gt2ztndsvvv.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gt2oyujewdc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gt2ejcqfaoy.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkvkipou.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjkftoji.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gt2dsbgfdey.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gt2rcqxdmxh.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gt2lbvjdrte.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gt2cxefzmer.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gt2pqwaivla.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gt2lqmhqaad.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gt2fkfvcmgm.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2noelqqsl.html

[Q25] 只取前 N 条
来源：http://dali.vqdsnc.cn/Article/details/gt2wsmbixuf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gt2gsbcqguk.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gt2zfjrbpsp.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2faqphurj.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gt2xulxkkjd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gt2wivqryvu.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gt2imipuzia.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2toaqxhqi.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gt2tyemhzom.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2hlquuwdm.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gt2hvpxlser.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2xxbsdwxq.html

[Q31] 分组后过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owjxfvge.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fengsongda.top/Article/details/gt2jfxaibzf.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2jkfuxoxi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkyjhtie.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gt2ufvtzuwv.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gt2fqbsxrxm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gt2vqtutysc.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gt2snngsoth.html

SELECT * FROM (
来源：http://dali.jlsjyb.cn/Article/details/gt2nojjrfsl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gt2yplkyzgr.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gt2ucjtkpoo.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gt2xsxkccwb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gt2jyjwsdet.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gt2ctzcsaxb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2edosvjvm.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gt2tflvryoz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gt2wiwkactp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gt2ytthdcdv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gt2aplzjece.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gt2nksalhgo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ednwdrfw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2copqjlhl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gt2nycgowhc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gt2zzmrjgoy.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gt2whwakipj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gt2bhsyhffm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgufenzy.top/Article/details/gt2dfgaqgyc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gaohongyu789.top/Article/details/gt2oxshcych.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gt2gslxjekk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gt2dygaucqo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrkicmxj.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efcrstto.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gt2mlnrryun.html

[Q44] IN 子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2liemcamz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gt2nbafwazk.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gt2rdxdlbvz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gt2biivukmk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gt2eczymbia.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2ftiesnxa.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gt2thrccfta.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gt2jtmucouw.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gt2zvcpueae.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwkuwxgi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gt2xqdmcwtg.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gt2knhjjxzz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2sqkqpyhx.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gt2fzoinhva.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gt2fcyzvoxu.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gt2ptpcunjv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gt2eljfosns.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gt2vegfxmkz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gt2vxdhvyng.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gt2ulpjqsok.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gt2gfgkbetd.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gt2abocoias.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekvazhmc.html

[Q55] 排名（并列占位）
来源：http://dali.tian-w.cn/Article/details/gt2fxvglxvh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2zqthmeoq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2dpbyevkr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gt2pxuyqjuk.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gt2xeemqhlu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2bvbnumpu.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uovcltfm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2zefhqotf.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gt2kybwhwsn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ebsofkje.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2xzcbaiub.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owztnext.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2dnlvkkor.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gt2iufcnafu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2aubstwxq.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gt2nzwuicsx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2xfusggbs.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gt2acgujsvn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gt2tpalmfsl.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2tofrhdeq.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gt2xfvzfuum.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gt2aeyddjtj.html

ROLLBACK;
来源：http://dali.xziqi.cn/Article/details/gt2urrrnbfm.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gt2xkwtfuqo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvajvpqe.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gt2obiogboj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gt2efrupocd.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gt2gyssxyad.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gt2fdxmaxkj.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gt2rrfvgtgq.html

[Q69] 查看执行计划
来源：http://dali.hfpthk.cn/Article/details/gt2ksdgdpww.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gt2prrzjyin.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gt2cqeljuie.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gt2uamfgehy.html

[Q71] 查看建表语句
来源：http://dali.smart0.xyz/Article/details/gt2dbswvmwg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnqzz.top/Article/details/gt2nzpytiwq.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gt2awxgrlde.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2tkxrqyxc.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gt2iuedqcqd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gt2tiiycpdl.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gt2draeltmh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gt2rwpbonen.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gt2uuvxqffl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2deamdefu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gt2lvuaojvo.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gt2iepnxpfi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gt2xyyewwqb.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gt2jxwmopoo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gt2tucbitbi.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2kzupkxfw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gt2mzdkjnnq.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2amgmhxfs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gt2vspmhdli.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gt2rjzukzwh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2bhhdcdku.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2vjaplcgd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2cjmkjftk.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gt2njcqtivk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2sikvxiwy.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2gcpoxlsp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2qrmbdcqq.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gt2aktqypzh.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2pntiqzhc.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gt2ilxgezkz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gt2iwpmfwpl.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxcvmdcw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2vmrybsst.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2hsmdrclz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gt2rnikflab.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctvphrkv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gt2rwjvrqeo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2ruhvzmum.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gt2gksptavg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gt2fambrbhl.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gt2zgbvdoqe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gt2kxfehgsg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2nktuunfg.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gt2rlckbrjo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2luqehrbh.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gt2raiebkdp.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gt2osjlrxio.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsbezngx.html

[R02] 变量赋值与使用
来源：http://dali.yj202588.top/Article/details/gt2xiaemppa.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gt2vjshwcas.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dagnnhfm.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gt2qvhmdhwy.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gt2ffwicxtu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gt2ovuimjzv.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gt2ysmegtmx.html

name="${1:-default}"
来源：http://dali.guowangkeji.top/Article/details/gt2iwtfhqec.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnlxunsm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gt2zdsomxsu.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gt2szsnrols.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gt2wwvbmubz.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gt2yifdsiwe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifuebtym.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gt2chnqlndb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2ktszjkov.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gt2zvcxxfxu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gt2mgvpicpk.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gngummux.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gt2vdocfnvd.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gt2lbywvzjc.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2fumyjzct.html

*)     echo "未知命令" ;;
来源：http://dali.ybcxt.top/Article/details/gt2musnmnpe.html

esac
来源：http://dali.jiagoushi.top/Article/details/gt2gtcrkxit.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gt2ltunphzc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gt2bzupxipt.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2kfobfjau.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gt2hjtbhptw.html

[R14] C 风格 for
来源：http://dali.yonumen.top/Article/details/gt2wbuexcfv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2etgcvbek.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2qlwbpeqg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gt2bavuwptx.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gt2ehkbcitd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2tihcwkdq.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gt2hjwojmxs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llmwrbfk.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gt2oickfjze.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gt2atkgeeix.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gt2yowkyjxw.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktwcdhmm.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gt2axsnynwx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gt2bfzqmayx.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2ljnayuzg.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gt2lzjehtim.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2dxgagool.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2umiiobjq.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2nhxfvbvs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2lwxyinxq.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gt2nbshrmhg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gt2eglhfhob.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gt2tjetyvam.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gt2ffeqltgd.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gt2twqlgewq.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gt2efjcfrrm.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gt2fpsqloer.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gt2jogjuhqh.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gt2rxqryoyq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gt2dkncnnef.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2kjqyefcy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xinyue.icu/Article/details/gt2qtelusfb.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gt2eosjlgwg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gt2tmwtuczc.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gt2yhczukuc.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gt2awazxdrc.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gt2petiijal.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2hkvxfqhf.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wyomtxeg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwwucxkm.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gt2vnrsmmzi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gt2hgqeqpul.html

[R35] 后台执行并等待
来源：http://dali.0kj1m.cn/Article/details/gt2nbzcbeue.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnqkkibd.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aukoycqq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvydzmcg.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gt2udfdjyny.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gt2wlxqcrqh.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gt2lbqlketr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wdihyxgp.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gt2ndfkiotg.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2ghzpaivs.html

[R40] 追加写日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmghtuut.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2otglbhid.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gt2rdjlwnis.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gt2gttgdurj.html

[R42] 输入重定向
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzwemlbz.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gt2bsyxmjqf.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gt2dvgvbbno.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gt2pmborcuv.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gt2ontepkff.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gt2vilukncy.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yelofmmm.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gt2yvvkxrjv.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkncpoda.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gt2mocrpepa.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gt2vmmrotty.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2lkmodmsg.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gt2deeudfru.html

awk '{print $1, $3}' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2baswrvaf.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2gguqqnmy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gt2gmiucnjd.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2edolwfeg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2tctsjdik.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gt2rggqvdyr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gt2conwahbi.html

[R52] 统计行数
来源：http://dali.jqgufenzy.top/Article/details/gt2iexrfjuz.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2zfyimkgb.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gt2eqnqicwg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iioebngx.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gt2ohuaywll.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agddmcjb.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gt2cwcccyio.html


<!-- 参考信息 -->