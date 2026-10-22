代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gt2wchhmsnt.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2sdbunwjf.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbuhmsae.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gt2axspgbgl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gt2nqohewxa.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gt2qmexuggz.html

amount DECIMAL(10, 2),
来源：http://dali.guowangkeji.top/Article/details/gt2jbscusgu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pycfn.com/Article/details/gt2wptzkbet.html

);
来源：http://dali.yuxming.cn/Article/details/gt2ccaxdthi.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gt2uoejbmol.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gt2mjltiaiy.html

[Q04] 修改列类型
来源：http://dali.hysaishi.cn/Article/details/gt2mbcvscti.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gt2ibzyvqae.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2nyiuugkd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yduswohz.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gt2xgmrrsuu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmxwuqs.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gt2umvyaaub.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gt2miufylwy.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gt2xzwqladq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2pkrlizes.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gt2wpctjyiy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2mmkhncpy.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gt2vzafzvkg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2nawijutp.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gt2poswpydz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2ncxasmcl.html

[Q12] 插入后取自增 ID
来源：http://dali.chenzaomai.com/Article/details/gt2bikxsvbb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gt2arrgifpw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gt2pjhrhevz.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gt2aqvfejra.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2cfzhdwvg.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gt2qzndcizt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gt2qhcrrlbz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gt2tqxrdbso.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gt2minhfmkk.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2ptfdwyqf.html

[Q16] 查询指定列
来源：http://dali.aizwys.cn/Article/details/gt2eckxlsup.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ksmsiooj.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gt2yizsoonw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2stwnkbhy.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gt2gscemzza.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gt2xksthmba.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgbbsrxq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gt2uhfrwjok.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gt2nvaibjij.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gt2ursvdiwo.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gt2ozucynse.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xziqi.cn/Article/details/gt2ohbuagzj.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gt2qepyxnmf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvnirred.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gt2vqoetpxb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gt2olulqcil.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gt2gymdsdlb.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2cfhspumb.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gt2vacwnzic.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gt2havakxrr.html

[Q26] 计数
来源：http://dali.yj202588.top/Article/details/gt2ealldltl.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2rpdsogdk.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gt2idxqaxcq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2mymvmqia.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gt2zrtnqivs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jckwzqcm.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gt2obdzbmbw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2mpftzjyg.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gt2qypkhyfr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qngaviht.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gt2ddpgagzb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gt2gkkbufpe.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnazilsj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gt2sntsmlht.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gt2jpqaubkc.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gt2swwvakch.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2tobocmbt.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gt2rmmgnvfn.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llavhtoy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gt2wqtrwqzb.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gt2cfygfevb.html

[Q35] 内连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqgfiupe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gt2busnnlti.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gt2npwgqtpu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2umulzuii.html

[Q37] 右连接
来源：http://dali.cdnleiting.top/Article/details/gt2hwzxgzhl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gt2flxohfjy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gt2rdlhgbxn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gt2swzioril.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gt2umftwywx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzgqskfm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gt2rbgycmtj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcidiaja.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gt2uzwgmkcj.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gt2ahruajiz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gt2gbhpkwwk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gt2lccgpiwf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gt2elvegyrg.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpdgxnht.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gt2bjewrwlt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gt2smsibzzi.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gt2idrzitez.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gt2fmucssko.html

[Q44] IN 子查询
来源：http://dali.sysykeji.top/Article/details/gt2rejijizo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pengpengdd.cyou/Article/details/gt2eualcrnl.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gt2vkylpwkj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gt2xhgszwnf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gt2abmazmth.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gt2abhxyfeh.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gt2kvwcvhvv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyzukxr.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2qdmncayk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.9152youxi.cn/Article/details/gt2uttvdvuo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gt2kruzdaar.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gt2kofrvwdg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qryhbjna.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gt2vwcpbasg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gt2fwxtxdfy.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gt2uofyqaqi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gt2dkemizwg.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gt2hcbabllp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnolwubw.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gt2hjqdyilb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cashguo.top/Article/details/gt2hnllucot.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gt2kveowqnm.html

TRUNCATE TABLE logs;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfqeysao.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gt2mwfprtcc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gt2avqskwsr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcnekhbv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gt2qztshclz.html

[Q57] 行号
来源：http://dali.kuanghao11.cn/Article/details/gt2yrtlljze.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2smtpmwgk.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gt2bpeohyhk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2otjlwfaq.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gt2nhvjwfgo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2inlitpks.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gt2ncruygur.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gt2vxwifgjy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2esjizcyf.html

[Q61] 移动平均
来源：http://dali.xuetiantiany.cn/Article/details/gt2ptakyenn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2tnqjbrsb.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gt2dyxlbnfl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2qwzzijba.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gt2trsobdjj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gt2oedlcugz.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gt2taicorud.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gt2tluigvkk.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2eotryiko.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gt2wfdfauqp.html

[Q66] 行锁查询
来源：http://dali.yanxiufei.cn/Article/details/gt2ylaexxtn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gt2sduzrhaf.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gt2golcunsh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cucudq.cn/Article/details/gt2sxdmeteb.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gt2uotihawy.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gt2bxksovoq.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gt2jaouadaa.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gt2psfifumi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gt2xnpnqbbe.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gt2nbdcywbc.html

ANALYZE TABLE users;
来源：http://dali.jianghu66.top/Article/details/gt2vjktdkwv.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gt2ayuhjmkc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmrfywfa.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gt2urefowty.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2iduweqtj.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gt2pykvjknk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ppjwa.cn/Article/details/gt2mvnccuon.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gt2mayyfcqe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guannengcc.top/Article/details/gt2tkvkexrm.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gt2ciyryinu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eikwnwal.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gt2httojadn.html

[Q76] 按天统计
来源：http://dali.cucudq.cn/Article/details/gt2cosccuxf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gt2ckwwytti.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gt2qfieoyik.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gt2jgellzfw.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gt2nankkxpi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gt2akwixwdr.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxkqwdtf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gt2pziqmtzd.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gt2ygazrxdl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2mlxfqbvj.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gt2hxxhisgt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2kjjpgqqr.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdivjycl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2wpwzptle.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gt2yaitzgrt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2ycgjkamy.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzedymzu.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2negowsqy.html

[Q85] 数值取整
来源：http://dali.xylfe.cn/Article/details/gt2mjpdcksb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gt2wpiuucwx.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gt2dfbuoefy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gt2igbxzrof.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gt2hqnjbbbe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jianghu66.top/Article/details/gt2wbhovocs.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigufen.top/Article/details/gt2dhvzaxhf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gt2ptvbvxxq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2avkyzump.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zymbhsrm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gt2yjewncrl.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gt2zuawiipi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gt2sulobvfk.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2jloisgog.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gt2ufxfrghc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jmaaoclj.html

[R01] shebang 与严格模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2carmadzu.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gt2iatpuptb.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gt2dxskxgim.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gt2kaeszbff.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gt2rfoauaip.html

[R03] 只读变量
来源：http://dali.ehwqpu.com/Article/details/gt2kwuhwlsf.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gt2thkckhbv.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gt2lxpdbhih.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzevebrl.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gt2bskgjhjp.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gt2bwhcccdf.html

[R06] 判断命令是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2fzncjesb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaitxhh.html

[R07] if 判断文件
来源：http://dali.mhx1999.top/Article/details/gt2ujulaymt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gt2xgiwwxzf.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gt2mymtwkuh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2bdjvgekv.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2dvfzzqyk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gt2ubzlxksi.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2voioaefz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqsnudfg.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gt2uxhoufmi.html

case "$1" in
来源：http://dali.iojbl.cn/Article/details/gt2ufhdgcmd.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gt2xckmrhhe.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2nmsbokpl.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2jgmerbiz.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnqvwjkr.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gt2cdlbgasz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gt2hpgbfiqb.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gt2tofedojn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2ckphpern.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqvkofbk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gt2czduxnce.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2thnwrwym.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gt2imbhfloe.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gt2hsxzsmeu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gt2mstsgbjy.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gt2pdmehudb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gt2hbueyviz.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gt2bvzjpscl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2itcfqvoj.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gt2dzveqsvw.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gt2ljjuabda.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gt2bteuqylh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gt2afgjlgdv.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2sjgrdnwi.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnixavyz.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gt2qsezkwzb.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gt2afkdaals.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2pbtjjbid.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gt2ibotpgku.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2pfoyfqhw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gt2lwprrwcr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srwbjrgg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gt2vsvjojrt.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gt2ykkwgdta.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gt2wskiqllm.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzqyhdzw.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gt2xoxvqsfr.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gt2skcgaipe.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gt2nbbehkng.html

[R29] 定义函数
来源：http://dali.yueranfly.top/Article/details/gt2blyqiqsp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gt2dyqqpqrn.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gt2cmqfeqdx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gt2vjyzlzme.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gt2pzvrzzkk.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gt2wzounhpo.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gt2olrxvttz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2lfzmxwce.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gt2plrltzax.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gt2chiricqo.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gt2hbkpuaff.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gt2heekvkfx.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gt2bvbjuham.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gt2nwvgkeau.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gt2wlbtaafr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gt2tgpqkqxm.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gt2kdljrkfp.html

files=$(ls -1)
来源：http://dali.ybcxt.top/Article/details/gt2esfkjhxr.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gt2ievgsmqx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhongyouzk.top/Article/details/gt2trtqusja.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gt2ofcldmjs.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2yicowxgn.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gt2wdqixsxi.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gt2vrykronq.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gt2grpnztsa.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2vzayxzpg.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gt2umaylght.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gt2pcswunqk.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gt2tqdwmrua.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gt2uybgqfug.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gt2xfurohvh.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gt2edkbdwwh.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gt2iuofwflx.html

find . -name "*.tmp" -delete
来源：http://dali.jqgfzy.top/Article/details/gt2ckrfbvnp.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gt2sbzstqzw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oavztujj.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gt2kzcmyhle.html


<!-- 参考信息 -->