代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gtqfnruinw.html

);
来源：http://dali.svipenyu.cn/Article/details/gtikgdsyaw.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gtcvrnqnir.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gtyhaxscjo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtqyuunldm.html

user_id INT NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gttlzjbobm.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gtwlzlqtuf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtnbueazlj.html

);
来源：http://dali.zhixingplan.top/Article/details/gtmugpvifh.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtawroufce.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtfosezzai.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gtyjqhjzca.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gttwxbvbiq.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtctcgtmie.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gtlgeetwwk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gtfbqbxjlq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigfzy.top/Article/details/gtgznuhwql.html

[Q07] 删除表
来源：http://dali.smart0.xyz/Article/details/gtusxfdsca.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtfyahfbrh.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gtyloajrah.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtdxdqmbtx.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaocxtat.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtlbwfjhry.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtklpzzefr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gtjbjrjgoz.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gtdtvuhrdv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtivgoqedy.html

[Q12] 插入后取自增 ID
来源：http://dali.xinyue.icu/Article/details/gtylecgxik.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtwreqssye.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gtsyhbdttp.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtfxhkwgxw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gtpexnokia.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gttdwyrfii.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtdncnipws.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gtuhmvjhay.html

[Q15] 查询全部
来源：http://dali.jianghu66.top/Article/details/gtwgstviwe.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gttgpxaubj.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtrcbrgklw.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gtjglerldf.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gtrsvtkiyt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzzqwzgs.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gtqavdritc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gtrdauhoje.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gtuczpdyuw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtsjwximhh.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gtivokiyqp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtkgqgqjzy.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtunridjek.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gtjgvhwytb.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gtxxiuvpnz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtbyfvxhqr.html

[Q23] 分页
来源：http://dali.hnxiangtu.top/Article/details/gtccychekt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gtokfmgxtt.html

[Q24] 去重
来源：http://dali.havefunace.top/Article/details/gtcrokmtrq.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtbomiijre.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpuxhlcz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gtkruhjwlo.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gtqndhhulu.html

SELECT COUNT(*) FROM users;
来源：http://dali.havefunace.top/Article/details/gtdxjhuieh.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtpnhyqozg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yvedp.cn/Article/details/gtsxxcfewp.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gtbodajrsz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtiyogisun.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbrsuynd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtfxzyrzvj.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gtuzxowqdq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtjwgblilm.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gtsizyxrgl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gtjfzwoqde.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtwfgpgnxg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtuwwjijhh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gttttrmgyq.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gtlaiurdcf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gtoebagbbo.html

[Q34] 每组取第一条
来源：http://dali.andypj.xyz/Article/details/gtzmvgfrfb.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gttyftfcml.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtrqytyxsh.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtxyseudvu.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtqaaplaoc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwzfvnhe.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtpatvbnlc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqcqzmsb.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gtgidhiudv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dashuyun.cn/Article/details/gtbhrtlyuh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtwleogbch.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gtmdtilmcr.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gtqwneqwwe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gtzxyvflgd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gtdzodtskm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pengpengdd.cyou/Article/details/gtospkfyjq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gtivmkdqly.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gtxqqnjgqm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gttblqzcph.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gtcblcbzqc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigufen.top/Article/details/gtraftepyx.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gtvzfzzzdu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.snrcjt.cn/Article/details/gtlptqbtrw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjzmhuja.html

[Q43] 标量子查询
来源：http://dali.nanxinkj.top/Article/details/gthnugcmkr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gtkqbrwpno.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gtisxiveiu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gtdmkggjbu.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gtdivychuf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtoeajhfuf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gtfbuoqbkw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtppzqkond.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtyovweujs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gtqeljoklz.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gtzlmhiqba.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gtdvjzckyw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtisblsqyc.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gtloaevuuj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtonapobpg.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyocnhwjk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtqvkdfdos.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gteczmzpyv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gtcncjdhab.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtxkvjaalq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlqllbdv.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtgrhbozti.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtptksuxsn.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjoehripg.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsyblhfy.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gtjiwrgapz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gtonwzhobb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gtebfhwxcz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtswdgjsie.html

[Q57] 行号
来源：http://dali.shuidangran.top/Article/details/gtmwzxqldt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtqovjjtxp.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gtljbysfhw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gtugcdiazp.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gtrrqfvtvi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtwfevyaar.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gttubzfyyh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtjmkgjmky.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtxlivcmbx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtrjpwhngx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtwdkmzwmv.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gtygenaibx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtlvrkvadr.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtsjeovfmu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gtjeqwtsgj.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtishhcupz.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtiwlooact.html

[Q65] 回滚事务
来源：http://dali.yonumen.top/Article/details/gtwqairawl.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gtvdjidamk.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gtotttzoho.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtbvbrseex.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtcfhozdmf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtfxnmhduo.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gtnpuvggzg.html

SAVEPOINT sp1;
来源：http://dali.316326.xyz/Article/details/gtvivgpatg.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtxgdaalcv.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gtymqjrubv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gtwedzkxjx.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gtbmyggkmd.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gtkidjwanp.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtwbepjiib.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gtmvbowdsx.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gtjcmkfkpw.html

SHOW INDEX FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtkysxfchx.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtugecevpl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtljoknkxy.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtusfztttn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cheryme.top/Article/details/gthfvrhqxb.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtnenertri.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxivvdlup.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtkggykger.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gtcybcjvvn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkfvcwnq.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gtqovpzadc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gttsguxibb.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gtqlmxkerj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gtilyrjgkb.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtgpgzlamr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gthfoaagnk.html

[Q80] 字符串截取
来源：http://dali.yonumen.top/Article/details/gtehzomatf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvpnhfmb.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtfnbcuuzz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtmxeuyctu.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtljrzdgwf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtzvcgzktg.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtvhltapxs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtzpqozkrm.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtbnulexsw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtwdyxvisw.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtfyoteabq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pycfn.com/Article/details/gtvcxzyztd.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gtfwodggwh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtdjmjulnz.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtefopldfx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.meibo888.top/Article/details/gtjxyjeuka.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtxduytrsk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gtnbnzayky.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gtpgdrzvma.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gtjupnknlz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtrinveouu.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gtswzqiggq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtxmzcnlpa.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbsnwjpwc.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtwoofifai.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkaayrnge.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gttulhhewx.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gtoqkuylhx.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gtelxykfcr.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtccbsbqhk.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtccbkbsvk.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gtkrlovune.html

readonly PI=3.14
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfcbfulu.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gtcxtwkchm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtrbdxrwer.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtroryxkgf.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gthcxjymzt.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtdiyrbsma.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtkxuvpqwv.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gtcaeclqpw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnsoocvj.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gtmnwlbrvv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtxumwzdcy.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gthduzmwad.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvnivkcu.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gtigeedcls.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtbopskfhn.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gtyqakdatz.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gtdebojpsz.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gtlvfxynjg.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gtbmtkpihg.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtrvridcjj.html

esac
来源：http://dali.yueranfly.top/Article/details/gtirxgxlxz.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtstxvjcng.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daria6918.cn/Article/details/gtoanbbqoi.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtzrsdunti.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtpvwwmyto.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gthswwhmkz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gtrzpzrjev.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtylkgypnf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlerrtql.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gtfvsoixbm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtaawhmiyl.html

[R17] 数组定义与取值
来源：http://dali.yj202588.top/Article/details/gtremgcxap.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtwsjpafpc.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtmuzyhckz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tianlin.xyz/Article/details/gtfngcqmwf.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gtdpftfmdg.html

echo "${#arr[@]}"
来源：http://dali.jqgfzy.top/Article/details/gtwxfohosc.html

[R20] 关联数组（字典）
来源：http://dali.yj20258888.top/Article/details/gthhqzszva.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xziqi.cn/Article/details/gtgwztqnec.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtsznvednp.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gtrznxbbbd.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtpribrvtq.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtrdmmpbvh.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtewktjnwk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtghxgqzij.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaodngslx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gteshqyoqr.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gtqylbnlbq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gtcotwpbhr.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gtvfdaoyhl.html

now=$(date +%F); echo "$now"
来源：http://dali.yanxiufei.cn/Article/details/gtpnzqzvhw.html

[R27] 算术展开
来源：http://dali.jqgfzy.top/Article/details/gtmyxjhdmx.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gttkhnxoch.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gtcmdfltyy.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwfwcnyc.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtkhqzhmyc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenlongwang.top/Article/details/gtxchlqzru.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gtiaakukag.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gtoadnocia.html

[R31] 局部变量
来源：http://dali.dianchejie.cn/Article/details/gtxowyyyhz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqcxcrbbu.html

[R32] 参数个数校验
来源：http://dali.yj20258888.top/Article/details/gtgmizosry.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtxrvvkapo.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gtplvgqhfs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gtinxqrdlv.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtxlnldoqu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtaptdcwsd.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtijcupnjh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gtnwtqisvw.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gtakuhhsqy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gtqfvzokue.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmyfgvib.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtwchyvpqi.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtowdcphek.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gtyhcusovq.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gtheesbsfu.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtiwojhhkj.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gtwzxzbyob.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtjjyfuvjq.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gtcllguxip.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtmkrahdnx.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gtupxaohev.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtaazamlhv.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gttqqzuddq.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gtculxvjxn.html

[R44] 按修改时间查找
来源：http://dali.vqdsnc.cn/Article/details/gtqovtmyjh.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtciaobnsb.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtcztjezys.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gtxoozflqm.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatoefusx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtgldtgbld.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdiwbxjo.html


<!-- 参考信息 -->