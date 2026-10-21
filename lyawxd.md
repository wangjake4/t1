代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtkaeplyjg.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtgopcxwxj.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gtbjxcqfmh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gtzmsjcdgo.html

);
来源：http://dali.hfpthk.cn/Article/details/gtjsxlskym.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gtemnkkgvv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.snrcjt.cn/Article/details/gtndnfxhzq.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gthzhoqyau.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtmblbdavk.html

[Q05] 重命名列
来源：http://dali.jianghu66.top/Article/details/gtiuqwwrvl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gtendqozni.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gttedfrird.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gtjcmubhzt.html

[Q07] 删除表
来源：http://dali.gotoacloud.top/Article/details/gtuatzplnd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtyxuwiyun.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqibjchzh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtaqshhanx.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtzggyfzvc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtvgbjxzye.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtrnrglkrc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gtuzukouek.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtcqtrelqn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtubgwktlh.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gthvuwhmsc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gtrupkwocg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.birdmap.top/Article/details/gtbqmwkqrr.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gttpnurkjl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtlhodvjmg.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gtpzdtqrxd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtnirxftgg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gtcgfxoeip.html

[Q15] 查询全部
来源：http://dali.shangyingyoupin.top/Article/details/gtrwiqokdj.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtfoyvpjnt.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gtatcyuypq.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gtaszcfidr.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtusxeupfc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtpidoreqi.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gtqnnjzbzy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gtgnltugmb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gtwifyeyzq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtxuqpwphn.html

[Q20] IN 列表
来源：http://dali.ehwqpu.com/Article/details/gtrfgprvrj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gtoaroqqur.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gtynuzlyig.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gtawxiuovh.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gtuzohnzaq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sxryk.cn/Article/details/gtglcosdxq.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtljmrvgax.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guannengcc.top/Article/details/gtbtsjggtl.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gtlmqbrtdj.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrodzfvib.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtlywbcfym.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyacabjy.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gtzfokduvw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtgdmvtezb.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gtpwqmkpfw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtrnyagmbm.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gtyoeiydaw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtestsdlso.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtlzkuqqgo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtqzsaoxua.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gteerooohh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvsooyxq.html

[Q31] 分组后过滤
来源：http://dali.0kj1m.cn/Article/details/gtjgfpuehi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gtkcoajqvz.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gthvtbtoiw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtejjlunkv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gtmylodhvm.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gtnwbfefrn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gtkpixvpul.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoqfxxda.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gtqcqikaph.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtcfksgpie.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtmtzbeumw.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gtjphfsyhm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtiuqvilts.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtmphxziiv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrndbkdno.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gtsbjaadil.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtepbepcwh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gtyxxnpkaa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtgttjnlen.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtiqmhzqip.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtznndvflb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gthhwmagnp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gtvzrshilt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gtiyqufljo.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gtgawbcfnx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtyyypmuul.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtiangpnzo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cheryme.top/Article/details/gtytqdtfzp.html

[Q42] 连接条件附加过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtikbysoom.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdatdirs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtnhgmnbdb.html

[Q43] 标量子查询
来源：http://dali.xziqi.cn/Article/details/gtynnakwvo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gtbabvodbz.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gtkrdmljvf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gtvlsrgyrh.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtisfxgkox.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtrfixwwst.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtqkvjjsou.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtswdqpgbz.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gthzaqecwe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gtwwztqptn.html

[Q48] CTE 公用表表达式
来源：http://dali.bjfxy.top/Article/details/gtlgpjgfih.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gturpsrgjv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gtorzcssrp.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gtmzplwgzp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtxpacvytk.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtqwskyttu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtbwfrhriw.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gtzebutrob.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtxicaoevv.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtewrkjwqz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtgvvmqgwg.html

[Q53] 按条件删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcicxvlkd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtsiakxcrg.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtpitfqehu.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtcgetekbn.html

[Q55] 排名（并列占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlllofiqk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gtnvfeserk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gtgddnkkzy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtwibtmcit.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gtdheanhou.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tian-w.cn/Article/details/gtmaknoieb.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gthppdhnur.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtcweaiibp.html

[Q59] 分组内累计
来源：http://dali.daria6918.cn/Article/details/gtjqlqphfj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwazzqank.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gtqmekhuyp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gthhqivdqo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtvxezeeke.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtykiymkbi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtjvvutcds.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gthfhgtvav.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtiovuhaco.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gtxleejbcl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gtlzsxricv.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaocfyxqk.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtqluathgp.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtfcbcgiex.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gtbzuroayr.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gtzxzrcdvo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gtjbfoubex.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gthpspnngf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtpmtfhyap.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gtvvoxmdee.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtinbwfqrg.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gtudqmybrm.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtkbwtwwmo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gtlwchqswz.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gtghfloviv.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwtnsxxb.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gtkhkrfgui.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gtuiwckekw.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gtpukjvkxn.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtfzedycie.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtmmdvswoy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtvseztzyi.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtriwlkutz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gtvhexuxir.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtfgrdrngz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gthdbvkdou.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtfqarhvma.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gtllrwczyd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gtgmsyknfc.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtmupqdyfg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gtossqdgye.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtzhomolfx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzcklimb.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtwwhbjatw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtiwikbkyn.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gttfwhndyr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtgxlxipla.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtkpxlwkxc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtwfvmwulj.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gtqhshbfqn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gthcjdixcr.html

[Q83] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gteacnckty.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gthufwkzdu.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gtaaerxzbx.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtidcljsxu.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehnnvfhs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gtlyuozygo.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gtvjkfqldg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gtiwafflch.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtgbinqeca.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gtnalscqkk.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gtblvlbwza.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtppwqycfv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxvcsxwd.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gtauzwhlfl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gtqcqprgzo.html

[Q90] 生成序号列
来源：http://dali.gzhubu.top/Article/details/gtqdwgumxa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtkibkscxv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfwwotmib.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gtgsqjpknw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcuvrfbuf.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gtdtyixrit.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gtnuboerel.html

set -euo pipefail
来源：http://dali.sufxvd.cn/Article/details/gtjetwnhqg.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gtwxvtxgzj.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvarcswcw.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gtajevbdnh.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtcvwnlfun.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gtsexfoseu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gtyixjqndv.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gtvkuszrye.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gtpopqgufv.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtymrvwpok.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtmjrkkttt.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gtjicigfch.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtqgcvbhjj.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtvtyymyad.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gtrgsejnhq.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtapncsonc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gtlwdhbjti.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtbnhdkgvh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gttrlwqecq.html

[R11] case 多分支
来源：http://dali.316326.xyz/Article/details/gttrzbnokm.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gthcndmrsu.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gtoqzwrijq.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gteojfiibt.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gtzmxgfbnv.html

esac
来源：http://dali.meibo888.top/Article/details/gtwdavnvrn.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gticasmuuj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtglwhoxpr.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gtvsjmuswo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtczrtxful.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gtpwseuloa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtwawyjxhk.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtyubhrmmy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gtidxcypns.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtgdmfvqll.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtjinpdrbe.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtzfogdfon.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gtnkpwejir.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gttgdvhhsv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjoikqfk.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtmkdhlbgk.html

echo "${#arr[@]}"
来源：http://dali.9152youxi.cn/Article/details/gtliuzqhqd.html

[R20] 关联数组（字典）
来源：http://dali.sysykeji.top/Article/details/gtzdweaeee.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gtxeotpnkj.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gteybwknjs.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gttlsheiun.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtcplkpept.html

echo "${s:0:5}"
来源：http://dali.yuxming.cn/Article/details/gtmznicxkq.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtmbizjymh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtbgmetmsi.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtagutyyna.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtyvgufvfg.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gtnpzixfge.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfxlokxc.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gttnxzsexv.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gtnaubouhh.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gtrhordjmx.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtsjukiige.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gtuigfniws.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gteojzoslq.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtqgoaeyfn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtnkstpfab.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtcbrykaki.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtxyvicnfe.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gtloqtgesu.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxuanxn.top/Article/details/gtiznzcozs.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gtwvjywydz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtpptxrmft.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gtftbrmtyb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gtjfbxnpfq.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtgvwmnuxr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtsyzbgeot.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gtqhjmkopy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtoaxjpaoz.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gtzmmfwogl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gtdarbytyz.html

[R37] 把输出赋给变量
来源：http://dali.nanxinkj.top/Article/details/gtimuwtdeq.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gteapcgigs.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gtpjpaowxg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtxilibgco.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gtyojsqorf.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gtnjouvixd.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gteuhmluos.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gtgjlavjiw.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gtwvhngytp.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtosnqqith.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gtnirdemcv.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlniwwun.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtynmhuquk.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtajxozaiu.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtbbbsmiff.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gtmmtefmgi.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtdcsaslip.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtfcmcsdsn.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtitqlmktl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258888.top/Article/details/gtremcprrn.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtbmsbysyb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtllxikjsm.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gttupimliq.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtgzvqtipz.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtdpadnzto.html


<!-- 参考信息 -->