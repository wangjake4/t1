代发 wailian999

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gtqixclolm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtpxcyhwio.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtggyvbuwx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gtjmwuneud.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gtxypaanmo.html

);
来源：http://dali.snrcjt.cn/Article/details/gtlgoagbar.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gtrsvaovzb.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gtkgsqabeu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtaedfqwjj.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtiqhakbhe.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gtblhumqbl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqerhhmm.html

);
来源：http://dali.jianghu66.top/Article/details/gtuvagyqnl.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtaudgoaue.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtnlsyahak.html

[Q04] 修改列类型
来源：http://dali.hnxiangtu.top/Article/details/gtavdlkxdp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtvfxpyoes.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gtrfosngrk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gttnnvmery.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gtmdurvepj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gtoongiwvq.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gtpcqwthvp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gttmvcltxl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gtxamrykzv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtgegjaqjk.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtqnoofbkp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxeodwvp.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gtaibfhmyh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtqqqofzpq.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gtksyshgqn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtundwyzrk.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtiuwywbfw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gtykcscrof.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.birdmap.top/Article/details/gtqldnuvst.html

[Q13] 忽略重复插入
来源：http://dali.dianchejie.cn/Article/details/gtoqzgucev.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtgjlehcwt.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtvsnrfunf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtuhauhrpt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zdqjudy.top/Article/details/gtieawlnfe.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gttqvnbwhh.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtmdjmsfoa.html

[Q16] 查询指定列
来源：http://dali.cqqwz.cn/Article/details/gtkoglaaro.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtksqiirat.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gtlpltwcfg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yueranfly.top/Article/details/gtevtapuxw.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gtdtyxmqvm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gtbpiolema.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtpqifhytz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtlfjozles.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gtjcszzkdv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gtjyujmnic.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gtwyzmwcla.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cashguo.top/Article/details/gtipqmwoin.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gtdcdztavs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gtmumrqagz.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsenbqhd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtoesdetmw.html

[Q24] 去重
来源：http://dali.wangdashe.top/Article/details/gtrxnnyrta.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gtwrpqeyba.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gtfqomhyuk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gtrkuyghau.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtjqcapcvf.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gtyxtvbeqe.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gtmyjhjewp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtiuaulizt.html

[Q28] 求和与平均
来源：http://dali.316326.xyz/Article/details/gtkltgrqvi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtvgskanwq.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gtxlwxvlrn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtptgshmon.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gtrpsqaylv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtjtfsiyuc.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtpkgjfnfw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtwvjibefa.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtypbuvciu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtlqhcfkyq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gtsnbwbhob.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gtrdtozgcm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtpoixxsaj.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gtphgiqynh.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gtkfakzbff.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gtsectmczf.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gttlspsdls.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gtuctopzcn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtsbvfsxfo.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gtvwchnjrv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtkekdvxsl.html

[Q37] 右连接
来源：http://dali.cucudq.cn/Article/details/gtzwfajxax.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sxryk.cn/Article/details/gtdnmcyvtl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gthcpusbzf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtubcfoizd.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gtdejmejty.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gttvzjihgv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gtapwhxzbn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gtjmolvrpu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtieswrypc.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gtriminfmx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gtgcfndhgx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gtvglrnact.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtwclqphvf.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gtxlsiuyts.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtfvbcagqj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtyknxdjgy.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gtcucanddl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gtszijcjsu.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gttivoybdt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gtujiyalzr.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtvjbbengh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtupriqklk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtscdghpwt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtzsthwsia.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtgczvytpj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gtobbdfndl.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gtcrziarmp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gtkovnxlst.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gtkrmoogtv.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtkdoqliah.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtptkzknsc.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gtjfjttnhn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtoxujsplp.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gtzojpvcbq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtllhcject.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gtctjtxhwv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtjninvdoa.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gtnkaubucg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtynodixkm.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gtyqoqrdul.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gtvnqqcoll.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gtxidabjdh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtgutfipxd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtppgqrojt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtisnyoict.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gtfifvnkwm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtigxyfiio.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtlbugifii.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtynfgmqta.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gtuxsnzbza.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtgosxpfkc.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gtpbiklocg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvutnvic.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtysjqdqgk.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gtuwoqxoja.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gttxnbikpw.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtzhxpaofk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncawwrin.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gtxsapxqvp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gtvxbochad.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtxodrvxue.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gtxnndmocb.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gteltuuhoe.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtcbdxmfvm.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtjpzukfub.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangdashe.top/Article/details/gtcxfkykif.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtdiahtsea.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gtfbszijcy.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gthicodsch.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtpvbohnad.html

ROLLBACK TO sp1;
来源：http://dali.yangfankeji.com/Article/details/gtaqlerwsc.html

[Q69] 查看执行计划
来源：http://dali.aizwys.cn/Article/details/gtvhaagrsy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxinkj.top/Article/details/gtfputeeqy.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gtnrzbmhkg.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gtqvlmvrwx.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtmrjoxsgc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtqskphyde.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtxlwufsyc.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtfkrmahao.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gtflwymupc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gtzqltukpu.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtslvwsjht.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gtorbvexnn.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtqqewldxs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubjnnvsv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtmtkgfsdp.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtjqifnnyo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.smart0.xyz/Article/details/gtmkubtvsr.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtrrjhfffs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gtlkzywcpd.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gttjkdnjcb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevonxzak.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtjohwffwh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gtschmpptf.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gtgvnjlioc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtswaltllk.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gthrkynalw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtfbtstktu.html

[Q82] 字符长度与字节长度
来源：http://dali.shzxlz.cn/Article/details/gtatliubgg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gteniiskyj.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtysuggnod.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtgogoyrfa.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gtpvnmdona.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gttlxitjex.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gtmcgiglyx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gtigwooszz.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gtvabvtqdo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yvedp.cn/Article/details/gtumeodrus.html

[Q87] JSON 字段做条件
来源：http://dali.jiagoushi.top/Article/details/gtpwvgbdjd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gtxgslntpr.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gtljwpccke.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gtliexbfef.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtsigalbbj.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtztqxwzpg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtsdlagjgc.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gtoyrzekro.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtiyncyhqw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtihtsfeon.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtlykwtrut.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgxkiryfk.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtcassouag.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gtqruqbefb.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtwywmmqqn.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gtviqntkqx.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtukrwszcx.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gtqnfjulrz.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtdzkbuwcb.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtrnyqfqiy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gtxhxfipkw.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtdbzgshag.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtcdmbftfi.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gtxbspucnm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtmlrarbcf.html

[R07] if 判断文件
来源：http://dali.xylfe.cn/Article/details/gtonwsvrsk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtkwbsthwc.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gtqboczwwl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtbwvbjqsd.html

[R09] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtffpqdxjt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gtawdnpeqj.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gtzlyjutwm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gtdyarvkmk.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gtpzdafoyr.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gtrarnbvid.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtasqgfbri.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gtkfikpacx.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gtqnhgmzac.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxkfosei.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gteadcvzjs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtexkzebov.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtnyuykkyk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtwbuajobs.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gtoybwboxx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtymduehzj.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtulsjuasi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtmduidedr.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gtpzaviocx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtagwfnbmg.html

[R17] 数组定义与取值
来源：http://dali.shzxlz.cn/Article/details/gtizmkpgzh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gtsmluavrf.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gtpmjugixr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtqmwwuuvx.html

[R19] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtferafruj.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gteztttfxe.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gtwiytueef.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtonjuayoj.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gtznypxrpw.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gttlouxebz.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtuxqaglvg.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gtaqeuqddf.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtnwznyllm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gthtbmshan.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtpdmpbpwn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gtmdmldpcl.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gtjjyjplqh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gtgsbdivru.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gtnmmkdeqr.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gtogejmlmr.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtljxojxyx.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtffjnisrl.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gtbydwbbzs.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gtjxlbrsdj.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtbuidmaua.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtztrwkuhg.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtayybfhoz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtsxhtqgxp.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtjrtmhobs.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gtrdowgnwb.html

[R32] 参数个数校验
来源：http://dali.cashguo.top/Article/details/gtjmpjyssd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsopaeqqg.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gtfftjferz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gticmgbefn.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gtywmutyfw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gttkxwjmif.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtebdfxqto.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gtxiczfgap.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtxrkvapfm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gtscehqosr.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gtmkrosvdd.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gthtenlxus.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtvzaeqoal.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gtunryzcbb.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gtvhsemxfr.html

cmd > out.log 2>&1
来源：http://dali.xylfe.cn/Article/details/gtbzkucppl.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtobwkdiha.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtbawqkumf.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gtecfyjrbr.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gtojaofzoq.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtqmkzocej.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoxvyrts.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtlagtuhhy.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gtaehbigbl.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtqxvbpgyc.html

find . -mtime -7 -type f
来源：http://dali.hnqzz.top/Article/details/gtqekpwrkk.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtszevhjff.html


<!-- 参考信息 -->