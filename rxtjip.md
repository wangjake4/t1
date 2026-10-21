代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gtrkkwczud.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gtgrrjivem.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gtwjaojhsj.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gtvztvdjpe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtufrexqaz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gtafztxlvv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqydjhhzd.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gtwoxwjuxq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gteryhjxud.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gtkbdmnsqh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtyhdecwca.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtlkatevhf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gtxfhvwuyh.html

[Q11] 一次插入多行
来源：http://dali.xinyue.icu/Article/details/gtgialjdnm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gtvmwbgyer.html

[Q12] 插入后取自增 ID
来源：http://dali.chenzaomai.com/Article/details/gthcdeoizq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gtiwgczkdg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gtwpztnxtl.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gtkmervonb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gtpdgpnmix.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtvlsjiqtb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtokzswxjz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gtnnfithsq.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gtbgygmkvm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtiwjnqdmg.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gtzzvajxlz.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtlnrrzkur.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gtqzceawct.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtaptgpwla.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gtosbdnihu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gtjfvabyuf.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gtyclzqwzg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gtdofmvyfx.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gtiuovzvne.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtuuwygutn.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtgsqjvnbn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtrvzxsmlb.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gtbfsvefcf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gtecvfkbxn.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gtnhrjwolj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gtrnbzyszn.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gtohizbmsa.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtfbykwfce.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gtlqynvoox.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gtybjkiaul.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gtzoygdboj.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtnfsampeb.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtwhbtjeit.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtbfzmlgli.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtpqhmuyak.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtozmateoh.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtmwvbadsr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtfgyiunas.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gtgaxjlmas.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtopzdjbpg.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gtekqyhqci.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gtlynauahr.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtzrzqmjzv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtqfkdtrqm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gtpkiiwgtq.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gtxxmpxtlc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gtoxnpweft.html

[Q34] 每组取第一条
来源：http://dali.shuidangran.top/Article/details/gtrnqafagd.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtxqlduzyv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtorwhwiva.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gtlrvkbmjz.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gtsmeqkova.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtlwsimnpo.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtevodwqxn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtlmraztul.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gtcfoqpecf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gtytcynees.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gtglttmyrd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtfkyiepnd.html

[Q39] 自连接（查上下级）
来源：http://dali.haohaochexian.top/Article/details/gttpvfnsgr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gtbexyfnwr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtkhlpazmr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zdqjudy.top/Article/details/gthylxubct.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gtipbflagb.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gtjpywgruc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtladrecqj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtgioyrqbr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cdnleiting.top/Article/details/gttibgrjsa.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtldkjusza.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gteodwziea.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtfvastmhi.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gtgurfenai.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gtcqqwmiwo.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqwbmkty.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gtrhyuggjo.html

[Q45] EXISTS 判断存在
来源：http://dali.daxiang520.top/Article/details/gtqbdocvnc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtxofufldk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gtxiyrqqiv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtfykvkbim.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gtxbzbdjaz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gtpkqqvaaj.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtehpuzspx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gtvmymlbiw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytpnvbkr.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtzipnwagh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtekjnogfy.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gtehkqstdx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgkdiifa.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gtnwzsksnl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtjckttmrh.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gtispepwks.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtfjtklltj.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gtttotodht.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gtxofjajgv.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gtbaffyhzz.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gtyhgzyuzw.html

[Q55] 排名（并列占位）
来源：http://dali.hfpthk.cn/Article/details/gtocmzxtrr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtczoizrpo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtvvvclhjj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtfvftnwqf.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gtxbvpjhup.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtpbcpwumj.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gtzszzyihw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cheryme.top/Article/details/gtmemgiykr.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gtaaqhjbfe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtzssaeqlf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gtghdreccb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtusjhvjzh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtaidzqvie.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxuhkgex.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtfhnfedwc.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gtjmzcpvpq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gteiantnlv.html

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpykcdwd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gtgwxagxaz.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gtflhbyjyb.html

COMMIT;
来源：http://dali.aibaodan.cn/Article/details/gthbhnbqki.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gtvveskysi.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gtrneibyad.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gtorzihkjq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtxmhqiqdr.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gtzapyousi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuetiantiany.cn/Article/details/gtggvibhfx.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtcriibscp.html

SAVEPOINT sp1;
来源：http://dali.tanke756.top/Article/details/gtlirhqigv.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gtvxsiafna.html

[Q69] 查看执行计划
来源：http://dali.aizwys.cn/Article/details/gtgiemiphb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gtcnqtgccg.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gthhaxrsjy.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtzxvpusww.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtfmtujvtc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gtgznvlgae.html

[Q72] 查看索引
来源：http://dali.birdmap.top/Article/details/gtiqxkdofq.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtwdjwyvmr.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtlzilyhqu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gtyasmumou.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gtpnewwvrx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtplncyzsu.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtcahcwatm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtlilpopia.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtkdgkwirk.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gtwadjktxh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtxaebzzoi.html

[Q77] 时间加减
来源：http://dali.zhongyouzk.top/Article/details/gtbuoysmnb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtyopceloe.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gtjrjczxeu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtejzkchsp.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gteldkoiqn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtishamdud.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gttenscpao.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gthjvxrdmi.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtvkvuvemx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtaxiwkncc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gtxzqfdzyg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtzeosvlvn.html

[Q83] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtdeaxfqou.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtcfrflutn.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtcnaqrmjn.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtxzkdbrwy.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gttdvidwoe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtcawpeakb.html

[Q86] 读取 JSON 字段
来源：http://dali.daria6918.cn/Article/details/gthbzjhkdz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizraxcel.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtrausyzku.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubhsfonj.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gtluporamv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gtzfdqqnkm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtuyjpxlla.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gtppszujpy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtcqowrjoh.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtgelennki.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gtmlhqgjvd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfntygrdg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gtalxgdalt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthdekamtg.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gtqhkqugsu.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtyathuekq.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gtmhlnhonh.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtdgevbtnd.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gtveuikfwe.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gtymojcoca.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gtqyrhdvhb.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gtpbccguxw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gtvxxjqisg.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtohxygybp.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gttxnphhsl.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gtmzessxch.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtjwiioxzu.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gtjjizfndf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gthlehgzlv.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gttqwwsqwq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtagrpilhm.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtvibkvplm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvcmrbry.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gtkfrthlsq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gtjrlpiqau.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gteztoouuh.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gthmghqlxp.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtkccbshgg.html

stop)  echo "停止" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtnaboftbv.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnsgaotv.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gtfijgykhz.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtfrpxhgpw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtbbzpamdv.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtaauqfyij.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtfwkjohkt.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gtnnzrfixy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtdharlrzi.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtdooxgtfn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gtjhelevvr.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gtnecxnhdz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxwyggxx.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gtfhydzptz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gtcrryltbp.html

[R18] 遍历数组
来源：http://dali.yj20258888.top/Article/details/gtzukvzlqu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gtbdzsauss.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtqxfyowmp.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtwheprwhu.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gtsvdnnwtk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfeqldff.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtqjgplfel.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gtvymssjjp.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtxhbguyue.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtjklqrslf.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtrupatulc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jianghu66.top/Article/details/gtvemixogp.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtogmpqrng.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gttmxpfqot.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhftbyif.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gtqwiwyjqw.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsdewkas.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gtnosapyjg.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtaikrghal.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtdggcpfbi.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gtgcajhjjs.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gttzhuotbk.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtblqburta.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gtdtlursob.html

[R30] 函数返回状态码
来源：http://dali.yonumen.top/Article/details/gtqqrsrjvo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.0kj1m.cn/Article/details/gtrejeehuv.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gttvasfrnb.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtkjucbwlg.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gtpjlicjob.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtcbamexxe.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtypljgltg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aizwys.cn/Article/details/gtytrkfunf.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gtwyfasflx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtpdrnaaet.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtywquhvba.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtlcvoedec.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gthejbxawy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtzjzwlzzs.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gttnxhbylh.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gtdkmtnenf.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetevqkef.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gtdaqmkays.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtaslvgktj.html

cmd > out.log 2>&1
来源：http://dali.cheryme.top/Article/details/gtyynydyxj.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhhudaes.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gtxuxqriqg.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gthglaqpai.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtdimoezrb.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtjrexctra.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtkwklgdqy.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtiyozvtpc.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gtnkbjzrhs.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gttqcrcmyb.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gtlhyhjbcy.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gtugxtpbdo.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtwwybxfxn.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gtpqlzwzxa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.birdmap.top/Article/details/gtkgapyhtn.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtlqkuhupo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gtvotxfbrf.html

[R48] awk 取指定列
来源：http://dali.cdnleiting.top/Article/details/gtthsbyboy.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtazlcvuny.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtbijdjfen.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gtfxkhkgoy.html

[R50] awk 求和
来源：http://dali.meibo888.top/Article/details/gtcnodjsyz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtugvaliag.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaqcljvc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gtuwbalndg.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gtmjoiaxqk.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gterhsvgee.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gtkxxdfnkf.html


<!-- 参考信息 -->