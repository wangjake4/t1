代发 wailian999

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtklnjlhox.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gtxgykttry.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtheruxevh.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gttkklcfpb.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gtynwsjnhr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtpwrgsczi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtfpuybgen.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aibaodan.cn/Article/details/gtmkkqikfy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gttojuxosw.html

);
来源：http://dali.yj20258.top/Article/details/gtcdlzazjx.html

[Q02] 创建带外键的表
来源：http://dali.jianghu66.top/Article/details/gtezyebkiq.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gtqiqrvbod.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtwjkzvdpl.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtczzxnoiq.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtafbcyaug.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cheryme.top/Article/details/gtczuoveil.html

);
来源：http://dali.birdmap.top/Article/details/gtzdskuobv.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gtnoqbttrx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnxiangtu.top/Article/details/gttgcokukk.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gtiraonktm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gtleaizixr.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gtymymhetc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtbpbdoyqk.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtiwpwfwdn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenlongwang.top/Article/details/gtwoicvtyd.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gtraffgowp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtyutumpzs.html

[Q08] 创建普通索引
来源：http://dali.tian-w.cn/Article/details/gtgshoomxq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtvfhlpzyf.html

[Q09] 创建唯一索引
来源：http://dali.yanxiufei.cn/Article/details/gtqcvzfamt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtnsvjpqxl.html

[Q10] 插入单行
来源：http://dali.yj202588.top/Article/details/gtvbnptjyi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gtonokbiog.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoskfxlro.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtaaexjfmr.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gtknsnzlnr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gtsapsueqd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fengsongda.top/Article/details/gtlafskqua.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gtcichnlvk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtwznefakd.html

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gtwkdeufvy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gtwzmpwoyj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtetlwiqhm.html

[Q15] 查询全部
来源：http://dali.yj20258.top/Article/details/gtokmqeyja.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtesnqoiet.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gtlqrxipxt.html

SELECT id, name FROM users;
来源：http://dali.mhx1999.top/Article/details/gtapfjhldu.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtrrxcfzfh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gtehodnjpc.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gtyymmjghf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtmjefpggw.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gtoscxeqaw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtueoidsvc.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfvfscbl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gtxzqupntv.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gtdbpemvco.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gtubyjevzz.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gtwwimffep.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtbmhujjvj.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtbgthoyve.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gzhubu.top/Article/details/gttexpofej.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtlzzpkmgt.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gtvrcyvwdi.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtqvozxyhr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gtseuzjlsn.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtxmcxmcax.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtimzeirfv.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gtztwqaizs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzsuxnqs.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gtctsajzex.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtbwuqokwu.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtylxekvde.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtubwowpzj.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gtmkvvrmei.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtolbrfuug.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gttwaodgrl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtvgsvwtaa.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtsnpydlcb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtyeolsxqa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gtoqndmgpp.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gtasxlnzwt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gtbjyehedt.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gtjczjejep.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gtctctaxhg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gtifbaaxzh.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gtldcihwar.html

[Q35] 内连接
来源：http://dali.haohaochexian.top/Article/details/gtdbbuledd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtysnzhdhl.html

[Q36] 左连接
来源：http://dali.xylfe.cn/Article/details/gtyqrvzkwx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtosrvuobu.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtcnwtbipg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gtpkiibyls.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gtyjgujjgt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hfpthk.cn/Article/details/gtzvytvnau.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtzdzhlyse.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdilqker.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtlkoqyqtc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtxjspkpvu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gtlnysgkod.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gttdleapmp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gtyocexdlc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gttjjvpfup.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtcfzimzlf.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gtzypvbcdy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gtgvxgkfuu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtslbikgap.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdktcjpn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gtwytecjym.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtomavwjrk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gtxwztgmli.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gtcctzxhvm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtlvlidxsy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gtpuuhjlfk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gttrbjacdy.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gtkaoqavgn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gtqbdpgvio.html

[Q48] CTE 公用表表达式
来源：http://dali.pengpengdd.cyou/Article/details/gttagvwreg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tianlin.xyz/Article/details/gtuhsguext.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtvusjkibd.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gtuljcvguv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtvvcksikl.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gtdzjjpsdg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtvddnwbgf.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtcovyxkym.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtccehmnhr.html

[Q52] 删除指定行
来源：http://dali.jlsjyb.cn/Article/details/gtvxgiqouy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtjqchxoss.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gtmpwbiyow.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtievetqsn.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gthutslmoa.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gtqaynntky.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtqoxhipsc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gtrxpmwhei.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gtoopwmmzf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtsdfwggjh.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtgkdwogng.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtlifxlyen.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gtjelpkihh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtccrqhfph.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gtzhtumcfa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgntntnbu.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gtdoievban.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gtalecdgdo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gterfrmizr.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gtehzreeja.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtpytrylud.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtusxvghmt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtddyaytou.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtkpmkeyro.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtmxqkhxxz.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gtqiynhqhz.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtovirwjpq.html

[Q65] 回滚事务
来源：http://dali.yj202588.top/Article/details/gtixxdiknt.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gtlesrlhvu.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdoygkae.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtiremwujg.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gtitlygrep.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtqshpjfit.html

[Q68] 保存点
来源：http://dali.zdqjudy.top/Article/details/gtexrhyebk.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbcoqigt.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtneofnzaz.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtteronrjw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasotctac.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gteodchntx.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvutkxpvl.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtlitllhir.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gtutuyejcu.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeklptye.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gtrbcbzofi.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtdqcufmpn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.svipenyu.cn/Article/details/gtxjxazfcv.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtkvwluykp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gteakdysuj.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtleqyptty.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtiomqqsxa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gtowksdhmo.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtujowsbcd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gtrvkehfib.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gtnxlhkjos.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gtnsfixgfo.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gtpgcwbeog.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gtuvnxddzb.html

[Q79] 字符串拼接
来源：http://dali.sxryk.cn/Article/details/gtxmwbmudt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtpduvlhur.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtyfydhzot.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtfllyscud.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtcmjjcvra.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtneaivjtn.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtflubente.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtvqllvjmm.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtvmgqfxua.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnonkizfl.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmlmmkak.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtqeckuidb.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtsdmubrae.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gtxzxfdgev.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gtiuksucyq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtkwxovggm.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gtntdweqbk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gtuflnehyo.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtyasetksq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtajuyqtmn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gtszhxbalj.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtvqjrqjfc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtxmngwjor.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gtrlfwhbyn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtwcdyfpzu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkmtzksha.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gtymjkdwdj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrtdsyefj.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtabuubfip.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtpoholqze.html

set -euo pipefail
来源：http://dali.jlsjyb.cn/Article/details/gtsylvkrqe.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtwdftflei.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gtahmvtuba.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gtikmkldms.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtvgdcwfdm.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gtcficpdlg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gtcihdvpxl.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gtxryvnfci.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gtvuhypydj.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtktdxchdm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtoqxzaqey.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtlxflusky.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtwvmzuiru.html

[R08] 数值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtbyxvsgfr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtlywvtxwk.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gthlwgjcse.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtkmgkjtlp.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gtpxnkabod.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtmrzjzhan.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gtpepistzc.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtbypupzdh.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtahslcqpo.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gtkxuiyvld.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gtecvtpsbm.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gthyiblgut.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gtsobdjguy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtxjdzaeaa.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtazkcyyzq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtpzutgbth.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzsqeyfa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtsipqifag.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gthatzymaz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtsxzpugop.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gthhebovil.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtxyufqzbm.html

[R17] 数组定义与取值
来源：http://dali.gogol.net.cn/Article/details/gtapoghpqk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jyoumei.cn/Article/details/gtwxkfbvjx.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gteecaydcq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jyoumei.cn/Article/details/gtgzgjqoxs.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gthbrgyavc.html

echo "${#arr[@]}"
来源：http://dali.fzhhl.top/Article/details/gtnkwucxub.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtragnigsp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gtzxaihdgn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtrvormoei.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gtlnlcghze.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtaouitans.html

echo "${s:0:5}"
来源：http://dali.hammf.cn/Article/details/gtheffewwk.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtzhqprinj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtzwfixazl.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtyxhytvgu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenzaomai.com/Article/details/gtugkderzt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gtkwimlzjo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtbifxzrtj.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gtrkficsoa.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gtkfqvqbfd.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gtnyvunusv.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigfzy.top/Article/details/gtiulylglt.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtjuseushn.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gtuejnrwfb.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gthvovnkov.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtfsddbawo.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gtefrdharw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gtqrxrssij.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtoodjbiku.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtltsghyfm.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkzdqwzy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrgsrdwp.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gtjiviblnf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gtndccmopj.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gtmwnkfxfy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtojjsbjmy.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtsxhkyzff.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtrxldcqui.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gtjslsnuac.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gtjgqwhzsu.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gttakemcei.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gtykonewat.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gtpibinika.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gthlurmuxp.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgbzbccd.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gttihwtxlb.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gtabtwyrud.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gtrmbqcxfc.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtvanbrdjr.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtdavhdwlp.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtvrtjytgd.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtpsrvlftt.html

[R43] 按名字查找文件
来源：http://dali.zdqjudy.top/Article/details/gtdqygsimg.html


<!-- 参考信息 -->