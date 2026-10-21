代发 wailian999

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsethzubp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtartqrlrp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrclumvc.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtversultd.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gtsoxgaprh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtuesqihwj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtynpsbqnz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gtnbbbqbze.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqlztbus.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtdfraxgkl.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtsvhvmleu.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gtnbafrbui.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtvtqvosnz.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtuxyvnzdc.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gtzsrcyrdh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gthltphnro.html

);
来源：http://dali.mhx1999.top/Article/details/gtqcrevcbk.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtccccblzr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gtpfihzixb.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtaepklmbu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gtrzolgyiz.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gtdojkilbw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gtvzdjuyll.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtzwvgbelu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gtfgrnsfwx.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtfujjdtci.html

DROP TABLE IF EXISTS orders;
来源：http://dali.meibo888.top/Article/details/gthwkaydvj.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gtfwurhnzs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtmyfvnjdc.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtiphrxfiv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtdurcsbln.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gtopzjgxfu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gttrqrityz.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gttptqgjcz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiybvhlp.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gtegbwftov.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gttowdahyy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gthwwhnxfl.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gttenqpnbx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtlonmxzwf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zycfv.cn/Article/details/gtpzimqkej.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtcluqjvzf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pycfn.com/Article/details/gtdimevwcm.html

[Q15] 查询全部
来源：http://dali.zhiwuduotai.top/Article/details/gtgihlzgch.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gtswzvnbxh.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtkrhztejw.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtixjpcxkv.html

[Q17] 条件查询
来源：http://dali.jinqigufen.top/Article/details/gttylkpeom.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtoujtesnk.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtgzclnrcg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gtpyqdvplu.html

[Q19] 范围查询
来源：http://dali.dashuyun.cn/Article/details/gtegtyceku.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ehwqpu.com/Article/details/gtxntemlvd.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtbtlhzpln.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gtrmfebrjs.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtytdlrlcn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gtlhaznzus.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gtzbudmylf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtxkoyukgv.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gtujvercay.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gticnegxkj.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gtrkncoazq.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gtygcabsha.html

[Q25] 只取前 N 条
来源：http://dali.yuanzhike.top/Article/details/gtfadlhejb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gtakhslhdk.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gtrkrrumnj.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtuxaykosc.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gtglottqkg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtunhppqsz.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxpmaxvm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtnpsziidv.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gtshkrsnzh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpugulsqa.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gtfmkuqgjc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtrfikksbv.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gtcynmiztl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtrksswcqm.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gtenurfpkf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtxmynxlnq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtetfwxxmo.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtofkudmzd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhixingplan.top/Article/details/gtuohsugai.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gtneicgtsl.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtngfdvyfq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gtijxwdrxi.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gtvicitpjn.html

[Q35] 内连接
来源：http://dali.xylfe.cn/Article/details/gtxnugudtc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsoxiuhi.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtthrfnbdl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtrtvjfbrk.html

[Q37] 右连接
来源：http://dali.mhx1999.top/Article/details/gtbbgtcpyk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pengpengdd.cyou/Article/details/gttigagkvx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtufmqsedz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gtyzrfybbt.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gtwnhokoep.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gttmotrroq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gtkbhweevg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gtlcjxdwor.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gtmnmxdsvp.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gtofqccknj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gtbxwmziwk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gtdgifcvmi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtuketxymz.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtatfyncfd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtmtqpjmvv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtmvjsexhz.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gthyfdssag.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gttwjuvilf.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gtinpwzdov.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gtjhcawyzy.html

[Q45] EXISTS 判断存在
来源：http://dali.xziqi.cn/Article/details/gtinhovvcp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtwyxgeyuh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gttekhnrqx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtzrkbwnux.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gtevmigvdx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gtvdahihzr.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gtaxejucjw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtojroxk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gttdsycybf.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gtpdzcbbtq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtddcnuocv.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtefrwbcfw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtxhgxnrve.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtcitbbemr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtnerribmi.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gtvbpsyzyp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtkrlkdrkf.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gtthiddcmf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtiyvmuzka.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gtcsvedgqr.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtfunuvlkn.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtjrhdonjw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtjmhgbldr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtzrqsaeyd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtezxmbirk.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtdeyyxrgf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtccggdrhn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gtlxcmlvml.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gtxhnnmwmu.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gtbpuezqnc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gthwewgczn.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gtiizxzkcy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gtmoyrpbtn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtinbgyykp.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gtkxothfqg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtbwlcefwj.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gtgshryxxj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtxylzsvqc.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtuagxloti.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtfnoijcdg.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtudayqleb.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gtbrrcqgsu.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gtkwssgmtg.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gthaleetzn.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gtpabadous.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtkpdrtsoy.html

[Q67] 设置隔离级别
来源：http://dali.jqgfzy.top/Article/details/gtunkpnpon.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gtyyvcdzwy.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtemuqiwvt.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwumqdpf.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gtiyftttws.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtejmnmnlg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gtqlilrjxe.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gtvhdcmuez.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gteppxsrgv.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gtioibbbnz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gtbumecnmq.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gtejwzjzjz.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtulqlcgzo.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gtaftcfbbo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtbrggxfyt.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gtzxcnpmiz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gtngwghlgy.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtpunvpvhj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtlolsrjtx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gtsxdrnlzh.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gtnmlchpzo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gtisrbkdii.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gthxescxdp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gtqlsjzruw.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtxpohdnpg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtqdenadgo.html

[Q79] 字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtznpugzjh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gtbxbvyshh.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gtfkxzekbi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtwvwqxtlr.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtdhlmemtc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtomxpjutw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gtgwzdhwlu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtcppxvneu.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtiqkjbsaq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtnvayukce.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gtbupcvelv.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtaiilcajh.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtblfkcytx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtmblbkuqc.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gtwtzfsxii.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtcutvnoav.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtmapcndnp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtsazmfjrs.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtpbzbeomu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gthfboqbzt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtjjuafknp.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtzicijbrp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gtvuuaxgvm.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtkivgxaiw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtttzerjlc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwhqvyhrk.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gthfjfakwd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfwywwoqk.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtoewghaqk.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtptleoeta.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gteswccatp.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtxjvrdade.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gttlmysakf.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtulopikkc.html

readonly PI=3.14
来源：http://dali.yonumen.top/Article/details/gtnfuelyin.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gtvhusfgah.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtpmucxguu.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gtmqldvknj.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gttkbrtcbt.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gtxngasufu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtwsnpwdlu.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gtdzjftode.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtirtkasss.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gttpvtbuic.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtspucgjkp.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquxwfzkv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gteckuzwxw.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gtdodytxab.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nwbrower.top/Article/details/gttkteljxs.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gtkevxgsic.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gtzvjfbmlf.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gttdbohtdc.html

stop)  echo "停止" ;;
来源：http://dali.aizwys.cn/Article/details/gtylkfzlnq.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtbmnxeohr.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gtxggaacvv.html

[R12] for 遍历文件
来源：http://dali.yongpay.top/Article/details/gtkmphnhjv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtcybavnhj.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtsgyqqaub.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtnmbngcbt.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gtzhucdtvr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtnigsknns.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtxnagxwmk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gticedvfcc.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gttcjqgxqs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtuvzkfqjj.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtuhtekwdh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipvlqepb.html

[R18] 遍历数组
来源：http://dali.nanxinkj.top/Article/details/gtwjnzslvy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gtfmijojum.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gtbqisinrt.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtvwkfmegg.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gtzvlrsplh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtmsnpnhte.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtpmfullad.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gtnspptldc.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtaabjlhtj.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtueyiheer.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjgamrsp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvquibjd.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtfmzikfhs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnofgpwp.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gtpnexxsyu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gtjqjttowr.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gttyqklxdo.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gtryaznlip.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gtwibjdvmy.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gtnlhgqtpt.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gtvhjocdan.html

echo "scale=2; 10/3" | bc
来源：http://dali.andypj.xyz/Article/details/gtzwnrwzpp.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtyiezvfue.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtqhybgptb.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gtlwtpfzhx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnqzz.top/Article/details/gtoqngwoaw.html

[R31] 局部变量
来源：http://dali.zycfv.cn/Article/details/gtefhihnav.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gtpcnwrbgr.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtgsexxxsx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtipxszbyz.html

[R33] 捕获错误并提示行号
来源：http://dali.iojbl.cn/Article/details/gtdcpnqwjv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gtvlbxswzu.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtzecaapco.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtqfieaeza.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gtfwwrvzyr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shuidangran.top/Article/details/gtnsqfxegk.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gtguyblijv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtkhvqksgo.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gtlxajyfnr.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gtfweobwtv.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxlgkefa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gtdltynhoy.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gtxvqleqtn.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gtleguzgrp.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gtvfklinax.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtfbjsogfo.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gtaejquiya.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtgmzmigpe.html

[R42] 输入重定向
来源：http://dali.zhongyouzk.top/Article/details/gtdajppmdl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtktvdfjpv.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtksrsmiiv.html


<!-- 参考信息 -->