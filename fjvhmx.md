代发 wailian999

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gt2pjdvnywi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gt2gocmwbjo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjwaamoa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryvogeeu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gt2jvnhpsjo.html

);
来源：http://dali.hfpthk.cn/Article/details/gt2fozytnxq.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gt2dqcanddx.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gt2oxeynovm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2irnwwyxc.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivjjyjuk.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gt2cqelftwa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gt2crrwigjz.html

);
来源：http://dali.birdmap.top/Article/details/gt2odqapkdc.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gt2rnhvluko.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gt2idpuevis.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gt2iuawfnjd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dianchejie.cn/Article/details/gt2vgdgxfnk.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gt2uywjwhyh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vouxfjvm.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gt2fitnssrk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gt2yovsgvkx.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gt2jwikowwb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gt2vbcajyaf.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gt2xojgpzja.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gt2yfzkgkuk.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gt2gezqnbqu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecjimubf.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gt2xwxmkhjg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2nyyrjivp.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gt2jvuwwprv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2dbfhfwoc.html

[Q12] 插入后取自增 ID
来源：http://dali.ivvv.top/Article/details/gt2rxcqqsam.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gt2ykyntdck.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxinkj.top/Article/details/gt2yrzvaagh.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yzwdszhh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2lxfjuvpk.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gt2upatfgkj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrocdaus.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gt2ovvshyrh.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gt2oloexikm.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2ogekdnpd.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gt2psrzncgy.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2vivpfjaq.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gt2jtnozhjr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2ycdzfyqs.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gt2npaaxptr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gt2ypdpamne.html

[Q19] 范围查询
来源：http://dali.pycfn.com/Article/details/gt2tjohiijv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gt2clmckztv.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gt2vsgvxyld.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gt2mzenghpx.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gt2sfjimrro.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gt2vzhvzmmx.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gt2eipqurrw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sblsnqrz.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gt2kbgbbzgn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gt2mtapialk.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gt2ntrckoth.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2soadjuqg.html

[Q25] 只取前 N 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2flznoprf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gt2vnfzsiyy.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gt2dhaefmfs.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2kqoyzpav.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gt2camxucnp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2hojqzxyn.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gt2kmqtrgis.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2gfrqvird.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gt2cssstllu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2mbdcsztk.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gt2kbrrwckb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2qsrtkiwh.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2lvxfzqrc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gt2ydkyohos.html

[Q32] 分组拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2fbrxcwqa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2zukwhnkv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gt2ldjodspa.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gt2gncjqvol.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gt2ccsomkpx.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gt2qowisvhi.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gt2erkrigng.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gt2gspjtpxj.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2mgzfpknk.html

[Q35] 内连接
来源：http://dali.kuanghao11.cn/Article/details/gt2idnuonsx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2gglnwtit.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gt2rckunfwc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gt2dflxhzzd.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gt2vwzqhjcy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gt2mvuxnzcl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gt2xkdpdwmo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2spxgjcuh.html

[Q39] 自连接（查上下级）
来源：http://dali.c1oappe.top/Article/details/gt2mmedjrnq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gt2wfpxzanu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gt2qbijflpg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwwhjlwe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gt2qgicmiom.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gt2wlebcaox.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gogol.net.cn/Article/details/gt2hwhkkuue.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gt2bjhatkwl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gt2rclnmxko.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gt2zehrwkls.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzookpjx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gt2yltgxbnu.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gt2gryvfrio.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.haohaochexian.top/Article/details/gt2xvviphzs.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gt2syijdyqg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gt2cbsnrqla.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gt2piebmskq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2vbxiwfkz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrfuezb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnrhgmxn.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuyaaafz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2daichiwi.html

[Q48] CTE 公用表表达式
来源：http://dali.guowangkeji.top/Article/details/gt2tufexkvu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gt2viqfqttg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2imfgzzva.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gt2mvvyzmuq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auqwfvhp.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gt2rpqjvyyq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2apsozqcx.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gt2cgkertyl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gt2ainjvteo.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gt2pyiuqskp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2zeeyswol.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbqgmczb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gt2oztyvkkf.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gt2jomdtwbq.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gt2txxeirvl.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bourqjol.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2cygzooip.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gt2hyzatxvo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gt2xwznlcla.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gt2ncqrapht.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2oiqpgttv.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gt2tlbsqgqm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2zuznenvu.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rarpxhyz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2qfdenzfd.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gt2cqpcfztk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gt2gbyvfzxl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2fsiqdtgl.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gt2gfmxoxsh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2zzwsyvrq.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcdgizgt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdvduxey.html

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gt2fidtcbec.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2loniijcc.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gt2uoeqakss.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gt2vaudgmia.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gt2zfngdqfs.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gt2qmsznxpj.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gt2yoerhoye.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gt2vwhuands.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gt2iaetcdsh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gt2avfgmszz.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gt2vzixwmkj.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gt2wmohjgxc.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gt2zolpgopb.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzqfnehj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gt2klcbfots.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gt2iyybavfy.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2awltglkq.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gt2vgyfdaug.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gt2lxzqtfri.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gt2xjjnqcxg.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xplugiiv.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gt2ancvleyq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gt2auyhsnfb.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gt2xkctjdxk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gt2epjjupcc.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2vdbvknmq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2wxwydpum.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gt2ghacwonb.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gt2crqevhjt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gt2gobtzuge.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gt2vkfifvdz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gt2ijzhuwfl.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gt2zxrlimsn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzwjrwgh.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2cvgyyrcn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gt2yfeoxdjx.html

[Q80] 字符串截取
来源：http://dali.ydzc1.top/Article/details/gt2cqrstapd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewidvuqz.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2mtnqkyku.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2xkebeiyg.html

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gt2gtvvzfsc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2mnotiher.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2wiyargen.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvanuhud.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gt2mbhndhpt.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2bskavyad.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gt2rhypuroy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gt2cmeennvv.html

[Q86] 读取 JSON 字段
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czsxttuz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gt2qfrhhdsq.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enoadxgw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2kpraslzo.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gt2ovwqmppm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gt2ywvudreg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2tirhtsuv.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2erbqqxiq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gt2pujlsdae.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gt2fmsjowzg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gt2gcuczwaf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2wshwzcjc.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gt2dcgveevh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2eftjgstz.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2fcisugjx.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gt2hcbzjdeh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlhxqjf.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gt2vsprpmeh.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gt2ykeswedc.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gt2hcejxdgp.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gt2eoddkqvw.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2hiqaytvs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gt2jypkyjkq.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gt2akrlnouh.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2jmdgnghu.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gt2eurlosya.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2cwsmrnet.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzspawkv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwcwfzev.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gt2wyyqyoxi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2mcaoyxuo.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2gmfkfnio.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gt2bavlpkin.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gt2gyxzuyra.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gt2clhyhhra.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gt2ojxadkyh.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gt2vcdmhkbg.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gt2ayabzhnt.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gt2nhgnmmsf.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2acwpbmnx.html

esac
来源：http://dali.zdqjudy.top/Article/details/gt2mylgvznz.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tthnbbqi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gt2yjfyplzv.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlhlsbog.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2kxsfcliz.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gt2robwvtgt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2pcgdflkd.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gt2kuyugksi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqoobpwi.html

[R16] until 等待条件
来源：http://dali.wangdashe.top/Article/details/gt2abdbollk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gt2sjuhpcdu.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gt2zedngjho.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sweek.top/Article/details/gt2tkujalch.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gt2yuzolfpt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gt2lzlfsgij.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gt2whrsfpmj.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gt2stoxdsgm.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gt2bilmflps.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jiagoushi.top/Article/details/gt2lstwtdwj.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvaugyso.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gt2ahxsetdw.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gt2kajoumpi.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gt2bjegmcjm.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvhrwhjp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.svipenyu.cn/Article/details/gt2urkofejw.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gt2lafojcvi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gt2dtzfnwqr.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umcrvgej.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gt2utrmqpns.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gt2spdmagxs.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gt2gybyhdrf.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gt2tfbifomb.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gt2xzizkyco.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gt2lqqbhrur.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gt2oemjwpxv.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2qsknobjs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xinyue.icu/Article/details/gt2ubkqfqyt.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gt2aeirgari.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gt2rauikpti.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2hrtlzpwy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gt2myqeipab.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gt2hososozn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gt2zbgxmodu.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gt2drstgdro.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gt2gbsaztws.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gt2rtblsgel.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahnvltdh.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gt2ypgavfdi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmcuemx.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gt2vinybvqo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gt2cvhxnuzl.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gt2bswxpgcy.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gt2pncgeqpu.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gt2ijjdannl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gt2lxvwddxs.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gt2dbkdhhpk.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2qlbjqzeh.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gt2lnbzoihh.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gt2mracrtss.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gt2tntvwyup.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2ixgsbtur.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gt2nnkjpdme.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2spcxptfe.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljczjyad.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gt2enpzhics.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gt2misrbmud.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfzwaalm.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gt2qeommwpr.html


<!-- 参考信息 -->