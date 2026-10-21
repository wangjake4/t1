代发 wailian999

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gtoadoaclu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtjlmustba.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtntqvbmqm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgufenzy.top/Article/details/gtfekqkxtg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gtxldgpitg.html

);
来源：http://dali.dashuyun.cn/Article/details/gtmjshltzw.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gtzzytchci.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gtucyilrbk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gturxncels.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtcnmvizlv.html

amount DECIMAL(10, 2),
来源：http://dali.sufxvd.cn/Article/details/gtdpctrzjb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtvpwxmlot.html

);
来源：http://dali.ehwqpu.com/Article/details/gthkjqpvmu.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtounzoxlg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtrrggqywg.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtsmbzheaq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gtwpjqiayh.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gtigqfynzo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gtqvwrmgzv.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtyjfwptqg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gtoqqwwsfn.html

[Q07] 删除表
来源：http://dali.andypj.xyz/Article/details/gtepvvtxdq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtkiruenyc.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtpygdhtgr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtrcjffnso.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gtsxqwuhvk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtxungwuao.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gtrruuydhr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtpebjkken.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gtlmfhhyra.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gtspdslibm.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzodakjcs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtmnwpxvot.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gttrnmtgyj.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gtrxpowqup.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtggbvivpc.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtnlggzilm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gtdxyzdfyl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtfmuyilbn.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gtvuodpbzw.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpcvyedu.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngjctcfs.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtbctfafkq.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gtphmmtncd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gttaloovni.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gtudodhvux.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gtnqlehlfr.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gtlrfrbcjy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ivvv.top/Article/details/gtjzzjmoqq.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtquhtpkbt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gthltxwaji.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gtcrdbfntg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cheryme.top/Article/details/gtozjhdoeq.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gtngenybqb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtawpowglx.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gtfbifpyng.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtbkiuvwgu.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtlzyzlvhu.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtbnygmytf.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtngrxfwfx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258888.top/Article/details/gtapgzksoh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gtmycfayeg.html

SELECT COUNT(*) FROM users;
来源：http://dali.hammf.cn/Article/details/gtnofolbby.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtcdhfewkz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gthrrijavq.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gtwcinbiyw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtdsuwnsjn.html

[Q29] 最大最小值
来源：http://dali.ehwqpu.com/Article/details/gtsgzgkvei.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtffxrbbxm.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtzlaynnlw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtfyxpibjr.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gtfyokkwtk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gtrgutgoyx.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtuapqiueb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtsrzleexr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gtiahtquml.html

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gtofqwbiqi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtcodxvoyn.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gtdxbvgikg.html

SELECT * FROM (
来源：http://dali.chenzaomai.com/Article/details/gtdqjmzjha.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtnufprzmm.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gtfxhgrrik.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gtuxyzcxkk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtzoptlsew.html

[Q36] 左连接
来源：http://dali.xylfe.cn/Article/details/gtyvtmoond.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgssgmip.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmampjdyr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangdashe.top/Article/details/gthslhvihj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtdueuxyyi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hongshengwenyu.top/Article/details/gttadvnszw.html

[Q39] 自连接（查上下级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtypqkczvn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtinqqbokw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gtuzeollzi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtdapmjray.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfiwsxbsd.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gtbqgqkxtf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtabuayccb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gtdhbrxrok.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gtaanfioqn.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gtvgkxqfft.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtgojxamaa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtpqcgtbsk.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gtluimoqjl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gteqgiwfwv.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtrjfvjcho.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tianlin.xyz/Article/details/gtvjwogpdk.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gtbxrxzafo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtjfavzcgh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gtcgbnryzc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtwizeqmoh.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gtmdyujhii.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hysaishi.cn/Article/details/gtrkyoipqb.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtlmkbzxhy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxqwysvt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gtnbhshsud.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gtxnkzhosa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtaffupemf.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gtjwqijkxa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtrgatyvpy.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gtypcfacqt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnizthgv.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gtbhbkwpvg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtgmjpldly.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtocuhvggi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gtbxrkveip.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gtwodqttgi.html

TRUNCATE TABLE logs;
来源：http://dali.shzxlz.cn/Article/details/gtwbfwmttx.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmtkurwn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtgteqvjoj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gtkyjdthpb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtszncxfxz.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gtfjdcpmzy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gtifkcxybb.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gtvvcomhji.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtzaebreop.html

[Q59] 分组内累计
来源：http://dali.feifeiyinyue.top/Article/details/gtlccleotg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gteuqftyoe.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gttwzyhbej.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtpoinkixu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtkkyrvejm.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gtcnkdfquo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtywoaqnjb.html

[Q62] 分组占比
来源：http://dali.sxryk.cn/Article/details/gtmitgmoke.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtcpkgqdxj.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtxaxvjkej.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtxdxifzgf.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtujpgwnlm.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gtyymjnlcn.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtkupakupp.html

ROLLBACK;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvjkbbkx.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gtheguhzkz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gtiypdhwav.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gtwctqusxp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtvqattkks.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gtutdujcyb.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gtvkxdnhll.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gtovnvhzms.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gthqisakva.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxinkj.top/Article/details/gtoclyyuap.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gtzqmczxfv.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gtyyiyqhlo.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gtyhejufgm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gttqeasnqd.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gtnxgljelg.html

SHOW INDEX FROM users;
来源：http://dali.sysykeji.top/Article/details/gtgafuivqb.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gtfhjymgpn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gtminuthbs.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gtegojyyhf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtgkbiauwi.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtifvdgwju.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtxtsssrrl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gtbutcumzw.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtqxlhbswj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gtnqtygswm.html

[Q77] 时间加减
来源：http://dali.cheryme.top/Article/details/gttlxbfoco.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtksarwbsi.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gtrxyaksuw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gtdlqzrgvv.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gtbxshexiy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gtkrgqqqju.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gtbykvzxuu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtubwsshpf.html

[Q81] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtryjxlhyk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xylfe.cn/Article/details/gtndlrhvag.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtyugttwmk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtjkynlagq.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtsvhqvbvo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtqntujiju.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtzihwjzgo.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtztatcoma.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtgyvitmvz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gtbarvybtl.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gtihskhvsx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gtytaniykf.html

[Q87] JSON 字段做条件
来源：http://dali.hnqzz.top/Article/details/gtzgaoqqmf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gtlnspjktb.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtdxwuzbsa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gtlakgsjsv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ivvv.top/Article/details/gtdtmojzki.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtnhonbajw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtzyjqioty.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdsaxugv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtofqiulgb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmdwxsjep.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gtgphrtueo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtvfpvwxzs.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gtvkxjsffs.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtrlwkgypw.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtmxcwcmkc.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gtcdmjrzsd.html

name="Tom"; echo "$name"
来源：http://dali.zdqjudy.top/Article/details/gtqeirmqpd.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gtwpcgyfhc.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gttqulhlyq.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gttgkldeio.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gttfblrpbl.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtptgzlmny.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpnraadj.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtwrouqofo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzjcpenrd.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gtgtoacmmi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfijcoiiw.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtjptlqlgx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gtodnimzxt.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtgwbizzeh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gtwwioihpk.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtjyklstfk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxinkj.top/Article/details/gtztwfoqmh.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtfudelupm.html

case "$1" in
来源：http://dali.zhengqikj.top/Article/details/gthamlksek.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtcmngqlis.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gthvscjwga.html

*)     echo "未知命令" ;;
来源：http://dali.xinyue.icu/Article/details/gtlupisere.html

esac
来源：http://dali.xylfe.cn/Article/details/gtpoolzgto.html

[R12] for 遍历文件
来源：http://dali.yueranfly.top/Article/details/gtpfyevkep.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtypigwzjh.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtpfppdoky.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtvjmhvxsu.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtazxgxhlj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdexddxwj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtjefufexb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gtpkmwryqu.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqxhvcfo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtzfyntgfv.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gtaysxwuvi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gtwqbqehma.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gtcyahmhgi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gtqtmijful.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtvshxfzfo.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gtxrpycgbr.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gtrcrfkkog.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtdaquczwf.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gthwwyumbj.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtupxqvbku.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gtuntyodnv.html

echo "${s:0:5}"
来源：http://dali.wangdashe.top/Article/details/gtimpdddyw.html

[R23] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gttmgckjlv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gthkxzrsbx.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtikudseiw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtzhrxzjxl.html

[R25] 去后缀 / 去前缀
来源：http://dali.kuanghao11.cn/Article/details/gtajqdpssj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gtivzkrygi.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmvoaalv.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaulfpgnn.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gtcgxoqans.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gtinfqnuwb.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gtdyokpdof.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gtjvfztcpl.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtdlousshb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gtfnypgcjk.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtgrckqbtg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtawlcwfib.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gtklwqfbys.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gtbllytlmz.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gthhpvjcus.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gthothgnck.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtfujxutoa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gtujbrzjrv.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtaauejowp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtxmpoeslw.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gtdribpqaz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gtkaabthvf.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gtpxiukwct.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtcvtimgie.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gtgldrnbin.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtgsnjlbaa.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtjlviyfgu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gtazlkhrsg.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtqmegxfoq.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtoicwxuzi.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gtwwuddwqy.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gtzvugvmfe.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gtgobsveev.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtrvahkodg.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gtgkhumexk.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkarecic.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gtpncisyrj.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gtzgqstohj.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gtramldvxv.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtgjutxijy.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtlgalytcg.html


<!-- 参考信息 -->