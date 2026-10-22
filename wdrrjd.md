代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gthgljjshd.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gtytrejldi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhzcqoco.html

[Q06] 删除列
来源：http://dali.yueranfly.top/Article/details/gtsbmhzdlz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gtqjqrrlyz.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtaioflzao.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gtoctunszn.html

[Q08] 创建普通索引
来源：http://dali.snrcjt.cn/Article/details/gtznfqoqbs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpcwabnf.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtnslwjqyc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtvgscrguk.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtrncaeeki.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtgrwytaqx.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gtuckhfhtw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtdzjvrtbm.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gtcpiuramy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fzhhl.top/Article/details/gtmcsrclga.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gtdovtkptc.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gtooohjuyp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtfgcyaczy.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gtjrvcwdqh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtyzxqjisz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnqzz.top/Article/details/gtwxmtanoj.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtjcjteirr.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtokzwacdf.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gtwxtaulgp.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gteqjafzmo.html

[Q17] 条件查询
来源：http://dali.cucudq.cn/Article/details/gtrorssfow.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtyvgfwxcu.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gtymxfkrig.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangshuangyany.cn/Article/details/gtsuawqcmr.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gtqyltxbzi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gthdzicbkv.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gtabksqxwt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yangfankeji.com/Article/details/gtisbcbiuo.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtckzywpml.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifkvgcpe.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtmymdxhqi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gttmnhhkam.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gtvssebhih.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gtxklzjnba.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gtlrfxjnhm.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtkzemfxki.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtbntaiqtw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gtusvvetps.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gthzdtehhe.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtfzlrhqvq.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gtgutxqjyd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtqpusqvoc.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gthxipaakc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtnvuuxxvp.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtvlhunshq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtgssdxtjz.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gtpeipwody.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtfwxuqtlb.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gtwtdixqdh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gtvherfeof.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtuccaykcg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtzycenfom.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gtwrhhjbqd.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gtctixeziv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gtgwairmfp.html

[Q34] 每组取第一条
来源：http://dali.fengsongda.top/Article/details/gtofbfbpjm.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtgguizmyi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtshlrspga.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gtysoexyjx.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gtlizpvnob.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtdldejojo.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gtvopqkhya.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtpmlogfll.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtsojfqaxr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gtehphaocm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gtmbhszqkx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtfwqgztka.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gtzkxjrsxk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gtauohqegb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtaomjowxc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gtofhxbwin.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gtbyqqfbvj.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gthuuieddk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gtspccafpl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gtdwkhawkd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtiydolesw.html

[Q42] 连接条件附加过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtqwpjdqwv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtjttiwvxa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcraswpqk.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gtkladuqwx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtwrijrrng.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqgwxtop.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gtrlmsunwc.html

[Q45] EXISTS 判断存在
来源：http://dali.cheryme.top/Article/details/gtwkwiaamz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtkczmdntv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gtwzujktbt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtmwwvxyee.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtzusryvwr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gtvbpotkbk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtlmiamxwz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gtbebmacus.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yvedp.cn/Article/details/gtzxqjgnnu.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gtstqkodac.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtrxaxuwnz.html

[Q50] 批量更新
来源：http://dali.havefunace.top/Article/details/gtkrymztqa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtleoxmofq.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gtefcpkyrg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gtxyzaiucy.html

[Q52] 删除指定行
来源：http://dali.jlsjyb.cn/Article/details/gtbdvqlqae.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtiruwrgth.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtohiuawmn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtqdukeaor.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpdljsih.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtwwbadfwn.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtsezotrje.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtostukntw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gtcltmacbt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtolrtikzl.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gtfzhuyrtx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gthbcrgvon.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gttljwvmjs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gtfbcbsuun.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gtpjjdrufc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtoewgxhaw.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gtvhmoegum.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtylcjdtvw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtogmfjqdx.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gtrqnqsktu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtexlgcdke.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gtuhwmtyiv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtlpirgqzo.html

[Q63] 开启事务
来源：http://dali.jyoumei.cn/Article/details/gttvpsrnee.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtqofvnbbf.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gthuehzpbt.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gtdmaijhmx.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gtssinqxvh.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtstdugnel.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gtgyhhkyel.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gtpcvnlkpc.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gtkivwdfjc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtokdqbjet.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gtacddcfhs.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gtfveuhqnr.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gtiashyprm.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gttriwhtzq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gtumriiarl.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gtdtmkgeev.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gtrqcjsmue.html

[Q71] 查看建表语句
来源：http://dali.sysykeji.top/Article/details/gtozbefjra.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtebpnkxhk.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtqmdzujjy.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtdlznzoqf.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtmmdkhked.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gtiblfxqii.html

[Q74] 强制使用索引
来源：http://dali.ydzc1.top/Article/details/gtzvwuqbke.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtycywgbdc.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtwcksqqmp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtqtbxsdie.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gttyjmrjiu.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gtfvjhpwgq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gtujpmhrxy.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gtqtldslki.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gttvsesslh.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gttvehfdtg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gtghvpcmzm.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtsbmxrtbk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yonumen.top/Article/details/gtgrpamunk.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gtyjxaryht.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtdveyuwbk.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtkyiqzkbk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtzciueceb.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtabjpaqss.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gttprmpkcn.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtusdaesif.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtpsbdxvaj.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpgclmqg.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtbwqfynkw.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfhorctx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtgbuhvldr.html

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gtqnkgfikx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtaefsucwb.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gtlrxdoxle.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gtqdpmebom.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gteorllese.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gtqedxjwzh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtydygzpld.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gtccndfzik.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtatpiczbf.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gtugrwobbb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gtmlnpamsp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmwbcvokr.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtokkquyep.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlxqwpbwo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gtuxguwnoo.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtqtogjysp.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtwatbfiws.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtooodudel.html

name="Tom"; echo "$name"
来源：http://dali.zhongyouzk.top/Article/details/gtdlpijxae.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtejkcplrb.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gtyhhpobjm.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gtbeqxztkl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guowangkeji.top/Article/details/gtcjpgbjtr.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gttvapceiq.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtjhyfeeck.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtxnpwzjwa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtehiueapt.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtslgjtkcu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gtlhpczenl.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gtqbopfzzl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gtckmwfxeb.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtxshwsbyx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjlqrtjr.html

[R10] 正则匹配
来源：http://dali.haohaochexian.top/Article/details/gtrevclrpc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhixingplan.top/Article/details/gtozhwnpaw.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gtcbpdvhjo.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gttfezfbpu.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gtaikhirtf.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtzpjvlwni.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gtuodedwgu.html

esac
来源：http://dali.cucudq.cn/Article/details/gtwawmkamq.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gtsztlwfrk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gtftrjmltm.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtkhvzcxms.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpbfkkss.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtazrrzthg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtdtprjuqt.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtotxumorn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtyikvgiqm.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gtjmncsffd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtsgaywpig.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtytfwnejw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtmphibvoe.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gtuexfuhzc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gtziitkndh.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtrqcupmbu.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtylotasbg.html

[R20] 关联数组（字典）
来源：http://dali.wangshuangyany.cn/Article/details/gtogfurusb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gtkatqwskp.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtvkcmqhkj.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtapeezcpq.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwtgbvfs.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gtfhwrmsff.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gthqcndgzg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtapffyitj.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gthvvcvugl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gtmkgshryd.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gtmuzpgonv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtsicqyppc.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gtlzypebnu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnirfwtmb.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtucrzfnqu.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemzqnwjc.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtuewyzhhs.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gtvoqfvaro.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtfouypnrz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gtuxhzsaun.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtztsmetnr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvtckvkb.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtzniciqwp.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtxcofkkno.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gttltnkifa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzirpaumd.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gtawvrambq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtsyivegdo.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidmapzgi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtvuenvstx.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtptzukddf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gtiizzdhwd.html

[R36] 并发执行多个任务
来源：http://dali.jinqigfzy.top/Article/details/gtagasbsxu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtwzvrdlal.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gtjvhakcet.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtagzzispb.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtvjylwcvg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtywkilffd.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtvajhwyyf.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtpcgwdwzw.html

[R40] 追加写日志
来源：http://dali.snrcjt.cn/Article/details/gtbndvqgsk.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gtusogucdl.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtapxogcam.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gtnxygoqfp.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gtmfqwqpuz.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gtysvgzfvz.html

[R43] 按名字查找文件
来源：http://dali.zhongyouzk.top/Article/details/gtkotcrszm.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gtflqgpvvh.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gtuiocjfwx.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtakgxvwkq.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gtffyysbjb.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gtbopgmove.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gtjmvwmzfp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtuslbnjcb.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtizimlcxa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjtidxee.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtnbhvlben.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtllpjvilz.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtoyfqxqgx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gtbkacrnzw.html

[R50] awk 求和
来源：http://dali.zhengqikj.top/Article/details/gtfziepvyo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gtggrbvogu.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtkmyaciud.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gtctdjkskb.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gtrdtrkgfw.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtweyuecfa.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gtvvurumky.html


<!-- 参考信息 -->