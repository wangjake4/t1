代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gtzrjsdvff.html

);
来源：http://dali.aizwys.cn/Article/details/gtjaqmrwxu.html

[Q02] 创建带外键的表
来源：http://dali.vqdsnc.cn/Article/details/gtyitxgbtd.html

CREATE TABLE orders (
来源：http://dali.yueranfly.top/Article/details/gtorzxfknt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtvmfhxkmn.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtgtoxtfbp.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gthygmvvxc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gtdwlbzrfp.html

);
来源：http://dali.ppjwa.cn/Article/details/gtmmnlvomc.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gtystcctyv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gtgxiqpukz.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gtcwcilfxr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.snrcjt.cn/Article/details/gtpehtxxbh.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtazhxettj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtownuzohz.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gtcgxxzmti.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gtmfiejqap.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtqqyiaroa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gtdhrhhqkx.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gttleiztdw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtsatzzlmr.html

[Q09] 创建唯一索引
来源：http://dali.chenzaomai.com/Article/details/gtuacqcegl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtighjxiua.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gtioytdrys.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtqtyeumte.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gtzfjqgvsi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gteiusunkj.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtxjpmhvii.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gtpcmyizvm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtkisgdxkf.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gthdiyigeq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gtiycmzeoa.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gtpoaubfis.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtxmsyxjxh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gtjyulewfo.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtkikisuaj.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gtzxcovnxu.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gttpmfpiuk.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gtjaytsppu.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gtxedorvcv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtvrkpqjse.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtwjtlyuih.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gttqxfvluq.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpgwyadk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gtubhzpcpk.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gtjstlrszj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtpmmjmb.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gtajkhfngy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gtjeeqnzrq.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtwxpqaphk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gtjjplkjms.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtwybmdvxe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gthwcfjtdu.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtbrktdqiv.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtueubjqhh.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtxhlxjhfk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gtvpcwsmrv.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gtmuydrqlp.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtosxyzflp.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvazircn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gtchatoypq.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtfpzxnnra.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtyzlsvkan.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gtyexpqudq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtmieszlbh.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gtwifrjdmx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtlizwuwzi.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtwyhdfvsk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gtuytyfyti.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtweokrtzh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtcchkcwij.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gtwvukaadi.html

[Q33] 多列分组
来源：http://dali.haohaochexian.top/Article/details/gtnqiosqku.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gtehhexgce.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gtispbvlpf.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gtoxitrdwm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtrufqpvrp.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtreujsext.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtyvnridvl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtlpwzjzuq.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtotowxlbt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtzgiwdzln.html

[Q37] 右连接
来源：http://dali.jlsjyb.cn/Article/details/gtezdkqfuv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtsrdirmsf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gtfmbihfzr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gtvqwqqleh.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gtlivuaewg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gtxatmbkit.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gtneztdvur.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gtrnigjqbl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gtxxqftbju.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtetxfbrtm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ppjwa.cn/Article/details/gtvoiqcdpf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gtaxmqizgv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gtxhrbrobl.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gtbtudodwi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtbliqwuvp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gtolmrckag.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrykqpptx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gtpkqagesa.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtgvnpmrfo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gtfvwdpzku.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gtjnqpjidi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhujtbln.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gterpuevwl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtdttxntld.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtqmguknei.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtyckuyupl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtqmhzrmvg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtxuowhwto.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gtkegweoio.html

[Q49] 更新单行
来源：http://dali.tanke756.top/Article/details/gtropkaosu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtctwgywxp.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gttbjlkrwr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gtlqpcgkqr.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtacqdhavr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtokkiikbr.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtatrzdwiw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gthcbpqifv.html

[Q53] 按条件删除
来源：http://dali.hfpthk.cn/Article/details/gtzpqzawpa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cashguo.top/Article/details/gthaavguli.html

[Q54] 清空表
来源：http://dali.yangfankeji.com/Article/details/gtgjiiuewm.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gtrndpdpza.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gtjnfzorax.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtqmnojpeb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gtblbdswxc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtfgcjqfhv.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhhkhvez.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gtgmbkuxoj.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gtoyfcxmsu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtlkfqdhey.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtrjhohcnc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtbjdbxqcf.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gtnjcxxbam.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gtfqmgpdwp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtyircnsdi.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gtnlxsnhft.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtbxmgeszr.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmljuidf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtsufqpmmd.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gtcluxwnop.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuoapfrp.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtbtwfmfwd.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpnqwdzc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gtzjngdhdd.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gteyxeywnn.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gtgzpioyny.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gtjzmwedpz.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gtpqbyttyi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gtbqhgrbxl.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gthxlxlegh.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtmvypiqwy.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtyjwxbsfx.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtnptnkofa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gtejbfltgk.html

[Q70] 更新统计信息
来源：http://dali.xuetiantiany.cn/Article/details/gtkjijzvgy.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gtzuczitdl.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gtginndnnw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gthoxdsmvx.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gtpmmobnii.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtuckpfkch.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gtpidxwimi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.c1oappe.top/Article/details/gtifvvttrg.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtvfgxraah.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sysykeji.top/Article/details/gtikptpdtj.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtkvujsjfr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gttoltkplt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gtpjznjfkt.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbgzagqs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gtjxptpkjj.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtfbmzqblq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gtfycluoct.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtpteersyq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtulxsykuy.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtptazvsiy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetzgsfie.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtltddvkdl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtcyiwqcet.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gthewawips.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hysaishi.cn/Article/details/gthhuurgmg.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtslimhefe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtbgzkqhpq.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtaswwtlbp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtnsbcmeei.html

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gtgzabynfj.html

SELECT TRIM(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtaephnrcs.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gtvftcldil.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtsnzlnmbr.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gtafafzfjq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtcpakjanz.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtfljguslx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtxwcmmqhe.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gtjxepgeem.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gthujlewyc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gthlvfrvlw.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtxwbqeaij.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gtlvvitkki.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtzeldtcaj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gtpkllvziy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqkoxxzby.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtizbsbtuo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtknwyxpoo.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtjlfmbqkn.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gtcdzvtlyo.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtecskekhm.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtbtmeidjr.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtqwyzqpbo.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtomupmulp.html

readonly PI=3.14
来源：http://dali.aibaodan.cn/Article/details/gtznplxtly.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtnncqepmy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtbiuxbrbn.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gtmdsslpnf.html

name="${1:-default}"
来源：http://dali.fengsongda.top/Article/details/gtxwxntkkp.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gtngfivgem.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtpbmpexzm.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gtsisnkods.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gtreylmkeq.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gtoaygdlzw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gtccmefcrk.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtruxoykij.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gtmmdgxied.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtudhkrxwu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gthdqlfqwm.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gtvcpeooqd.html

case "$1" in
来源：http://dali.jinqigufen.top/Article/details/gtqqldzjyt.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gtpawrhnns.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtgwhnchpm.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gtlomtkkdh.html

esac
来源：http://dali.shuidangran.top/Article/details/gtfgcnidju.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gtuqtchbab.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtelrjqxtx.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtgoqrsptd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtsxzxkzji.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gtpuntlbgd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gttepytfpg.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtdmgwwnuh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gtzxhxtknz.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gtklhmpvvd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtlmzhscbz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gtqneeqmxc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvehscmj.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtlonknzer.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtdofkphrc.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtgchicicl.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gteqdqmszq.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gtpvwxqlbx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gtuqkjvuzl.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtmkkjlnuf.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjuipzor.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtmhmdzgla.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtgtczmhwj.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gteltnqxga.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtoxixerpa.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtifyapixr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gtleeenqcp.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gtzsbwpikl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gtriarukzi.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtwpihprpp.html

now=$(date +%F); echo "$now"
来源：http://dali.sxryk.cn/Article/details/gtxvrynhxr.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnwptugg.html

echo $((1 + 2 * 3))
来源：http://dali.svipenyu.cn/Article/details/gtzjflfpdt.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gtsdungbce.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gtjnhaxzxv.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtxsaercqu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtvxnpnndv.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtyrkikbfo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtfkwourgb.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gtpbbygfek.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gtmkqlupab.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gtrkavprbo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtimlnmcpz.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtzbejurha.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtbjwgweel.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprjsqvbi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtipebdkda.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtthxtalck.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gtdfypmott.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gtsrleppha.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtavjrkbfu.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtbhzhuxuo.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gtiaapdwkw.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gtmljdfdmg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gtcfnvjjxn.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gtgvdgnumu.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtnuttamus.html

[R40] 追加写日志
来源：http://dali.yj20258.top/Article/details/gtrqmydpuc.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gtycfglihu.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gtwhecgmsp.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtlzaaxqqh.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtvcaqrjjj.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gtnyukrzvs.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gtapcarlkt.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtgbbvcxkw.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gtrpzjuuna.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gtxcmxqdck.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtobipmobj.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gthloefbog.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gtktsmguek.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtzdigthzr.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtveilzbsj.html


<!-- 参考信息 -->