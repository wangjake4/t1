代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gtkrsoyhfu.html

);
来源：http://dali.xylfe.cn/Article/details/gtftwaqaph.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gtbkgoqexy.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gtfgmulkan.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtbkkleegl.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtlbohxsnp.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gtjqcuatsj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gtqbsrigve.html

);
来源：http://dali.tianlin.xyz/Article/details/gtqnaxtwox.html

[Q03] 增加列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgytjehn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gtvyxaonpi.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnmmzzcd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gtkpjtjufn.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gtizsgulht.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gtsuycoqex.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtidhkonzq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gtihyazoef.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gtwknbtvok.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gtastyemkb.html

[Q08] 创建普通索引
来源：http://dali.snrcjt.cn/Article/details/gtrumhyqqc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gthhgfhuqj.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkebturk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtprvvquom.html

[Q10] 插入单行
来源：http://dali.zhixingplan.top/Article/details/gtcdsgneht.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtbzrptgse.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gtjdmnaiix.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gtutrtuvec.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtypaoanjc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gtmzhyqplg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtfkohzvnj.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gtulgxtmzu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gtkkodfwuj.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtxycvspzk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gtewbxzdnk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gtvtzboeru.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gtybmvdfir.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtssqqhgvz.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtlzzlqjoj.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtudadhzjd.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gtthrsrzqd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gtumrmicuf.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuzgqwfz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gtjnvnslfd.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtnnttzakm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gtugwbzvzu.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gtkxfpohvo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gtwbgqdolv.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gteeozdfdy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gtdeakqomj.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomnwvgxd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gtngclybas.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gtgtsjvpkk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gtckfynumb.html

[Q24] 去重
来源：http://dali.guannengcc.top/Article/details/gtszbmevou.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtmoywbdix.html

[Q25] 只取前 N 条
来源：http://dali.feifeiyinyue.top/Article/details/gthmdadvkd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gtihwkbpmy.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gtfemtqsbh.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtzdkyedho.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtaeosfaxr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gtangqcwff.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gtgwkkztbq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtuorsamix.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gtyshxddem.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjeozjkuf.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gtcocjeqte.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtytukdmmm.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gtchuxggcd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gthbyjinvf.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtaqrmzeuz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gttlmbsvtu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtsogzspdq.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtgtsclcbj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtkvswuedo.html

[Q34] 每组取第一条
来源：http://dali.bjfxy.top/Article/details/gthjtxblrc.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtyhbvdwrh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gtjfbkdkhd.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gtdvqutbrm.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtwexhbxbr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtibhzpqqe.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gtyoidmgka.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtlwrnqiwc.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gtbeaatsni.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258.top/Article/details/gtdpgkkwzx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gtqjrmatld.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gthgycnhhw.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gtexowkhbl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusuuisfy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtexrakszo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtndzadhna.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gtrmpomojq.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gtpcbhalgv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtorqclzof.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zycfv.cn/Article/details/gtirclfduk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.iojbl.cn/Article/details/gtmqjribsw.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gtbqwguoeq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ppjwa.cn/Article/details/gtctecekay.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gtecnrvhue.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtdrzgbaiu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ydzc1.top/Article/details/gtyrxdfirt.html

[Q44] IN 子查询
来源：http://dali.svipenyu.cn/Article/details/gtsbuavdor.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gtuifvgsle.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtblnyjxyf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtxyansvfn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cashguo.top/Article/details/gtbqyhevfw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtdsgwkjsh.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtztdnviza.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.haohaochexian.top/Article/details/gtauauzyva.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtkeuondxk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gtywegsqya.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gtatzdndwn.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtsnejhgdi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gttijrdbbl.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gtnsbrxbwp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtiyhgpcdd.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtmwjctspe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gticaknsaw.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gtipdtpnkr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtzhadovdr.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gthsfdkeiz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtisxwktua.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gtidqkyvrx.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtptcgtcrr.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gtbqlqydan.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtyyyeiudr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gtabdixqyd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtlyblvnvn.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprrctadb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtwcdklwkf.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gtdnwipqnq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtkathlbuk.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gteduzhuit.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtywgjdera.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gtavhtjmrh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gtgnualaqd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruzaiham.html

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gtpsuqtywu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtunpuxrcl.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtwqdxdrkc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtftkktssu.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtpaeuxaqf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258.top/Article/details/gtcnmhhfhy.html

[Q64] 提交事务
来源：http://dali.zdqjudy.top/Article/details/gtwasutqxv.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gtfvqeprvz.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gtowummrpp.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gttopptime.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gthyseixys.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gtxdbhsuoq.html

[Q67] 设置隔离级别
来源：http://dali.chenzaomai.com/Article/details/gtmzinebcb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtelqvelmh.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtnjorzrmv.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtypwgynwz.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gtsrrfrxhn.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gtggujprxx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gtvapbxwdq.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gtrhglqycb.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gtwsfqunob.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtqylljjgs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gtpddrbeeg.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtadoxvzvw.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtjodlvtxv.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtlvunrocq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gtuziaxanh.html

[Q74] 强制使用索引
来源：http://dali.ydzc1.top/Article/details/gtvyxiqlpf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gttyyofaen.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtxspdfiml.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtivcjunqf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtcsqxyncv.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtkwgmlijy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gtmkewafup.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gtoylcynyo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gtfuqikjnt.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gtdketrayw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtvlpnrpnp.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtrdbrenco.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gtqqesbvwu.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtxahdhhqc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtsrtpmpla.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtfnkzioog.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gtfywdwimn.html

[Q82] 字符长度与字节长度
来源：http://dali.aizwys.cn/Article/details/gtezirguuf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtrssoptkr.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtknvbvhsz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtjgwjzjxa.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gtqzybwops.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtspwuruyw.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtgiddwlfr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gtkzcmnsjf.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gtenhbizpd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gtwvmietfq.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtabmjnotc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtpfeuknzy.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gthuueuppz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gtvgeyvkgj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtdwlubmwt.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtrygetcuo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gtruzphlhm.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtpqwdlbao.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gtogyxohbl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqyhymsih.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtlqyanqsq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxkhrrklq.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtcgacwbxv.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtttsluhfc.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gtcqpryyta.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfnspehe.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gtssihrrim.html

[R03] 只读变量
来源：http://dali.tian-w.cn/Article/details/gtwgdlyrbx.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtzpntgajg.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gtcnsvrvzm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gteyxdtret.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdhjnpzu.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gtqxtnhzvh.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gtjcnqsuvi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtkpsmywwv.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtqpoilfjb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtinwcmkvd.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtqevajmak.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gtumsbhlcp.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtcnwyrvpk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtjxwzzyqn.html

[R10] 正则匹配
来源：http://dali.haohaochexian.top/Article/details/gtydtstach.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gtoduexdyp.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gtspwdvjoq.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gtfdapoudu.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gtvhldvoqw.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtnrauabca.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gtznqzxwvu.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gtghzxdpcq.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtpvpeivhg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtewyuecdz.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtflclvuig.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gttmyrbune.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gtodunzlyl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtjeiqsgxj.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gteeghhxde.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtdemvptwl.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gtxrfgmhzw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtqatepzuf.html

[R17] 数组定义与取值
来源：http://dali.sxryk.cn/Article/details/gtlpdutovs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gtutnrgmzr.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtlhqoiwjq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gtuqmboays.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtqkvtvpti.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtyltkonak.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gtswspdaib.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gtywkfkxcy.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtpbolwnvl.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtabavgrey.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtgjmaalpt.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gtphajnmfd.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtifosbcnj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtdnhrnsel.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtvkcnztev.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtehvpdxgl.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqszoskb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gtfsqfnbeg.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gtxuusbbfb.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gtetzrudqt.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtwsebgkme.html

echo $((1 + 2 * 3))
来源：http://dali.gogol.net.cn/Article/details/gtebqmjotn.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gtzukahbjj.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gtqrdohvnh.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtjvzshodi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gtaebrylks.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gtsukzrcoa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gttfneitaj.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtxarejlii.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gthyjvbsiv.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gtabnhcojp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtlxiqncgh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gtwrugyuyu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtimherozp.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtscbyojzn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtworylwrp.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtdezxkjle.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gtaypmxvtt.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gtjtcnsvvc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gtborfdfdg.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gthmywtyts.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gtnukhqxid.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gtmsrvwaxh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gtwjusajgv.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gtbjfepktg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gthcuzylvx.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtwkjisxvb.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtxzrcaoql.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gtyuebavsn.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtnusrkgdc.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gtfbomvujy.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtkelssqgd.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtkoxljkbn.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gthpvhsybz.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtmawgvcnn.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtwudzvtip.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtjsktnfnl.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gtqcatwhjv.html

[R46] 递归替换文件内容
来源：http://dali.yj20258.top/Article/details/gtxfjzdzeu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvfyfwhf.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtqmmgnyql.html


<!-- 参考信息 -->