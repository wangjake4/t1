代发 wailian999

);
来源：http://dali.fzhhl.top/Article/details/gtrudrsyym.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtlfllpepc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gtsuoziyvk.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtmfpeyzwz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtqwykrflr.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gtvamfezeq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gtsjsvicgr.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gthigpgzpo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.birdmap.top/Article/details/gtetdnskwp.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gtxywccomh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gtzksviquo.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtwxpjodvv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gthcaewmqp.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gtwepznkgo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtgrqiywfd.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gtukxcytcz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtblugknrd.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gtmyvwcgdy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtvvirthvo.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gtouwyzfig.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gtdhgafftz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gtbpfehdci.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gtavdwlcbv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtnvbpaqbl.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtleacucfz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gtqtihcrjq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gtfldkhtce.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gtniynbaru.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtimjrkqad.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gtawcnkkdq.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gtvslaksvb.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gtgtjlojyr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieskuztp.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gttvjkmrmo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gtacwziyyy.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtvjiyukot.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gtoneldnzx.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gtetuelixe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gtcpmdwuxt.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gtnziqrfwv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtpmefesna.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gtnwdxaing.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gtqpazhjwr.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gtxfozccqd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gthlnjbmso.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtupodmiwk.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gtxmyxcieu.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtrvetbyuu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtqrfqxksk.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gtxakqfmpl.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtrauluoec.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gthgcycpen.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjicqncy.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gttlsuguvm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtlazbompf.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gtikvvqcny.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cheryme.top/Article/details/gthjsmqdgb.html

[Q30] 分组统计
来源：http://dali.hnxiangtu.top/Article/details/gtxyfvlwyf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtrsabvlje.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxpevwcw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fengsongda.top/Article/details/gttuenesdx.html

[Q32] 分组拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtmgbqwqxs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtrsrfeeoz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtimqcznng.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gtfalgpfba.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gthmfzwvwo.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtikbylupd.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gtvkcpiaaj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gtiiijriav.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gtcjlrnpve.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtlfvrsclu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtlgmsiiqa.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gtrphmogti.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtotzjfydz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gtieqklrlr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gticqolzji.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ppjwa.cn/Article/details/gttqdmfsyp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtwlezhodt.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gtrzcjeuzt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtaflluahw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtkgzppxvx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtpoicciph.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtniugrnhq.html

[Q41] 多表连接
来源：http://dali.yueranfly.top/Article/details/gtpucpbjsh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtbebvhedc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cashguo.top/Article/details/gtdouiyqcd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtjjycnlqk.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtyoolhuqa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvkewoel.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gtlgqxcmrn.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gtzosuqbhz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gtshfhsvnp.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtpsfzcqpw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gtrwmhgzan.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gtdanoknwd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtxdjnaboi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtkuacgook.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtblynghia.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gtjajzgwti.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gtlyyeyhjn.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gtmmkjifom.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtazfgapsq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtgzhompss.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gtoftgbied.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtctinyqxx.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiodjinkq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtjygdbgwz.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gteawuxbmx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gtzpjsfqwr.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gtvtyfrpuh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtjcenogzg.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gtcztqasma.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtvgxwgaiy.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gttnoisuyt.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gtzasdfcrh.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaaogkem.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtolnzbobs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzvxpean.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gthlpqgfcj.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtzicbimxw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtejpgiacz.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtebgkamvg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtfavgepps.html

[Q59] 分组内累计
来源：http://dali.pycfn.com/Article/details/gtvzocosud.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtnxstdwde.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtqynurzau.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gtyxaillef.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtgoblhavz.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaxaybjs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtnejumyhy.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gtbzobbmda.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtrspxylil.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gtkyqrzrhf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gtiuyprtsd.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtrplhunns.html

COMMIT;
来源：http://dali.ivvv.top/Article/details/gtlzgpsrak.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gtvyzydqsy.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gtkkwljuas.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gtdhkpcjep.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtrizgemxx.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtmrulobct.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtqshqmwxf.html

[Q68] 保存点
来源：http://dali.hnxiangtu.top/Article/details/gtaggvakve.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtyjvrxahk.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gthiutcpat.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gtiavbcwot.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gtkoxlvgsw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtyfxbqjnq.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtvvxikopb.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gtcwfvecjc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gtairaljvp.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtomkffkvm.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gtdeplauco.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtbbsvsbwi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtaggbeoym.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtgmppiiub.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gtgbvxupgt.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtdslslshu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqewvmyg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zycfv.cn/Article/details/gtuqajbbba.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gtqsncvhts.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtvmdqgcqx.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gtspuawhnz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nwbrower.top/Article/details/gtaptbkghe.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gtejvtmvdf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ehwqpu.com/Article/details/gtgtxnhkas.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtfmsorsis.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtvacymcug.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gtyinghatw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtsxomwyqk.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdvgkfcn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtubchaaow.html

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gttrdaratt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtwqkqjgsj.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtxwtgdtwd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtgtfswoxs.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtllozkclc.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtjbozvlme.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtyqnhzxxp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtqseekulg.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gtmtkytsci.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gthkslddff.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gttspyprje.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gtazpolhve.html

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gtipfpygyc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gtwrlzumdu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtuzdihros.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gtlgpuiufm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gtuztjkpkq.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gtxpalzync.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtrqxonkjf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmqletbas.html

R. Bash 专题
来源：http://dali.9152youxi.cn/Article/details/gtfkbnkcqq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyoyhebtl.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gtpxwkkkam.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtvpqjbtur.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtlyaludcb.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtsyyfubti.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gttxqfhbgd.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtfjsywhov.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtrrasgjjt.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtgqtglbnq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gtvdxbrkag.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtwdsldvkk.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtfjhnwdnd.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtoioyslnu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxazcdoe.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gtvdugszkv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtlfqyqrce.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gtskwlqoyo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gtlvtcmgwu.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtrzdzwtog.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gtqdazcxbw.html

[R10] 正则匹配
来源：http://dali.iojbl.cn/Article/details/gtoijnvpgf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gtumfhhfhs.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyexrnvw.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gtlyzfwuyv.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtwxkgjoeo.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gtgyvcmnnf.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtyxmgpcis.html

esac
来源：http://dali.hfpthk.cn/Article/details/gtpaoubgzp.html

[R12] for 遍历文件
来源：http://dali.yongpay.top/Article/details/gtjchhmtyk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gtisfwhrzs.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtdebszval.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtwvxhyria.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtjgwbxnel.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gteglialeq.html

[R15] while 逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtqpipqbea.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gttbtwqxle.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gtdbsqycas.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsfmcddg.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gteosyrgwg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gtqvbkpkzi.html

[R18] 遍历数组
来源：http://dali.c1oappe.top/Article/details/gtjbfitmed.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtsnjvfzdj.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtahkkyrdt.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gthqzjztxx.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gtnotqrels.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gtupasgban.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gtfqihtbip.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtbwancyqy.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gtttwjmhwu.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gtmbtawkct.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtuvavuxfg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gttyplytbq.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtfgjxpfwi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtjmziglfq.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gtxyxffypz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gtdvtdctlt.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gtwqdaiccl.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gtsphdjpbi.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtmwbponbz.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtskyaryci.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gtetxjppev.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gtswtqvukk.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtwdbcxlvb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtseiwtnoq.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gtmvrnoqsq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gtvtglxyqx.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtokkxrqoc.html

f() { local x=1; echo "$x"; }
来源：http://dali.xinyue.icu/Article/details/gtwgzhwtgt.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gtduetdhfv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrlosgjj.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtmvdijmlr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtuawsxcas.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gtdxfybvqt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtpxaillxu.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gtspsnjhtb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gtloergdlk.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gtgljepffv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtwufunzmc.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gthbsunimn.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gtqmidlnrc.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gtffrwvpkm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtstsjvkfz.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gtuxjbiteb.html

cmd > out.log 2>&1
来源：http://dali.meibo888.top/Article/details/gtsuuuzehm.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtxznjvmrz.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gtugqlzvfk.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gttwlzlmts.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gtcipmkpkj.html

[R42] 输入重定向
来源：http://dali.kuanghao11.cn/Article/details/gtggvgzpkz.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtvvelawhj.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtxlzoaqve.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gteeosdnzf.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gtacqkogqv.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtqnzwxkff.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gtjlydtlia.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gtogltmhsz.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtrdpezofd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gttiexrqvv.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gtjomhzlyj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gtbzedxhot.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gtvikjgdpq.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtpsafmtar.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtkirlgmad.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdfyzxtc.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gthtqvjodz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtexituptt.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gtfihdcdyf.html


<!-- 参考信息 -->