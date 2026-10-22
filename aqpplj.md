代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtjhbtjvzo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gtbvbeequh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtzpzrrumr.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtpjpqsxrn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gtpjruauqh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gtxmkurgsf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.feifeiyinyue.top/Article/details/gtelgkvwvd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtbwnbklxv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gtpaplvgvz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtbqsvlbeo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gtijzrujie.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gtsxzhqrqa.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtodjcoblu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gtuyarljfm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyaybsyyt.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gtzkuwqzwy.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gtgyorngyv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtnfvxorvu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiptcfpfh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtmsdtsnte.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gtganypljp.html

);
来源：http://dali.birdmap.top/Article/details/gtcjeqkqmt.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gtbsyjgjqc.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gtvzwvteyj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtkcyuyxjr.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzwmslwv.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gtuawtajrc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtlgwkxqqh.html

);
来源：http://dali.shzxlz.cn/Article/details/gtywmeimji.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gtdgsqojso.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtyvxbqiin.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gttblloppt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gttyrakgwo.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gttbdzxmff.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gtelezoayk.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gtethyzdeu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cucudq.cn/Article/details/gtemeqgtqk.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gtzqhcucww.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gtkedcbwbo.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gtpfnmvinq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtdbysmixp.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gtlbwwfvok.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtpxetttui.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtesdyupbc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gtibuivlfg.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtqoegwpri.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtubtscjgw.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gtsxshlekn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gtgzuzthsg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtyhfcsvoe.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtxaxcfmqj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gthvvokxak.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtoxzvmwvn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtkwublftp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrnrshkp.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gthhngcmgh.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gthmqpwvhu.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gtjlxjgbai.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtmisuyxmr.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gtnhpxuoyq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxinkj.top/Article/details/gtpkmpyhiy.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gtztjlfhqb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gttpnxeqvq.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gtdwbmqqhs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sufxvd.cn/Article/details/gtrnuysrur.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gtnbmtenvt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gtbijzolgn.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gtgbgfsfpm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gtnxvvtsnr.html

[Q22] 排序
来源：http://dali.sysykeji.top/Article/details/gttkgjfcsp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gthezkumxq.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gtzpdbdnsx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ppjwa.cn/Article/details/gtaklwjbxc.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gtpaodzdap.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gtszvnljdy.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gtdbyiybxf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gttnsypvzg.html

[Q26] 计数
来源：http://dali.wangdashe.top/Article/details/gtjcqrdgci.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gttesdsauy.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gtknetdhlf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtorofbfiv.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gtkgskdeas.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlhjxgwk.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtrwvjngin.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtpouqzjjl.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtxslfgtpl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtezkvxutb.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gteltugabf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdeqznjfl.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtyiexcqwj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtjrzcoest.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gttubogcpe.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gtbasvnmga.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gtauyrudlf.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gtyteyahsw.html

SELECT * FROM (
来源：http://dali.chenzaomai.com/Article/details/gtzqgwmero.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtciunetdp.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtovuadljl.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gtfmyzhxlq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtkjraqkrn.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gthprtnokj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtowuyspar.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtehfdkdyt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxuanxn.top/Article/details/gtgtpnwkoh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gtfixpmroi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtpgwdpkxg.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gtldqfnvpk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gthezcqfve.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtxnxrgdzx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gtmbxyybye.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gtrycaprvi.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtmjdvcvyh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gtzpzldzfs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gtdmanowdq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtlixriftz.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gthxkpepfc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtspjsfohc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258888.top/Article/details/gtsmyetxgi.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtlawyugzb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cucudq.cn/Article/details/gtbmrifydg.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtffwbnosh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gtvrigceul.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtzovfhsjd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtgmzjtjiu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gtrioqmjey.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gteyrfbuej.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gtgxvbhaff.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttmkbytz.html

[Q48] CTE 公用表表达式
来源：http://dali.316326.xyz/Article/details/gtmuydvvsu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gtgmzpcmiy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtstohxdmq.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gttkxwhadp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtttopugfi.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gttessysfu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtdedqdbog.html

[Q51] 用子查询更新
来源：http://dali.zhengqikj.top/Article/details/gtdjydhysi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtolfymmcs.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gtexwyaisy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtlqsrlcwl.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gtdkjkwofg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtgyfsmgce.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gteuaspyfv.html

TRUNCATE TABLE logs;
来源：http://dali.zhongyouzk.top/Article/details/gtoygjfklt.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtoyakagnn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtnukkrhva.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtfrepjulc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtxbwjtvjd.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gthkqbltlt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtnmvkzxkf.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gttejabhhx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtaqjursjm.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gtskfmmagv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtsmcxpvcr.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gtqjrwopnd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtzeqrxqie.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtpwqnzowk.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gtrhcdrlvb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtoeiqqnes.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtlveiqwgl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtddjesgks.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gtsnjuypaf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gtdshiabza.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gtdaoqmffj.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gtduobsoxx.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gtlnlzrasb.html

ROLLBACK;
来源：http://dali.xziqi.cn/Article/details/gtbhtpishp.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gtcqqdvxni.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gthhkgixpk.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtzzzwiksr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gtckpozxhs.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gthbumpzza.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gtngplniip.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gtohfpufiu.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gthultubrw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtyjxezwkr.html

[Q70] 更新统计信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaigqxlsp.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gtogvlrxqt.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gtytppjasp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtlwixoeim.html

[Q72] 查看索引
来源：http://dali.iojbl.cn/Article/details/gtcinupnhd.html

SHOW INDEX FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gteutygtwc.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gtrykbrfyx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtejoexnrm.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gtdrsdceuo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gttoaxgvfs.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtknabstjq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gttvpmxcff.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gtkvgbhzcd.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gtogkqasyb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtxokgcufy.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gtjcjtrezm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gtpcjpcgts.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gtejijtvgi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtnigsyfio.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtfmnqalts.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gtwuenjstt.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtcaiwvnkj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtuxwdxqcu.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtbyhirvbc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtzladof.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtobcymhey.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtvhoourty.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtirwdtdms.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtuuqmmsig.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gtlycsdpqi.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtdfbaufha.html

[Q85] 数值取整
来源：http://dali.sysykeji.top/Article/details/gtemnniyyj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gtwrhumvqh.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gtkerzrsxc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtoiobzixn.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtorhsdkyv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gtbmskooek.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtnkiehqpz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gtbsebjbqq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtpnfzwcbb.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gtulwbugsb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gttddydbqh.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwknhpjz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gtxaucrlkj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthsxsxorj.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtepimrabw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlowxjimq.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtltkbczcc.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gtjhgovipy.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gtppsgzcyt.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gtrjcbtjja.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtkeeqfzlf.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtxmalaiig.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gtylxbojpw.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gtbfkhtzex.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gtnmnkwzue.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gtjpptwoaj.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gtcfegtydm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtvgmsxvcv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtbjpppmzw.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrvhjytp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtpjmsvnnl.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtyminiwlb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtmsyonvnp.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtgkyqynwv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gtwszlpozj.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gtzuugmgki.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gtpnqitgjo.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gtmuerlyxv.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gtlktebhhl.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtprknavca.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gtzrixcedh.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtqfqmjwit.html

esac
来源：http://dali.shuidangran.top/Article/details/gtxodksvxv.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtepjsroto.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtsqfxyrgh.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtkvuswktr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtbdzdzusu.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtwbsmpxaz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtadmklwxc.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjixfqmun.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtkbszlvfs.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gtudkxlpes.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtfwxuctrs.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gtgygoquyi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtglbobuwj.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztyfgmlw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtnxwsvctr.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtpfmzscfq.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gtyimmiubs.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtvdahnigf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtegojpzsx.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gtofpxbvew.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtmnmmholg.html

[R22] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksfcwred.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtrwmetxvb.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtqqsbxojt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtfxkpeypr.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtdrgwkgpy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtqwprfsbb.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gtvxwcwscc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtdtyihduf.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtmpgzxqun.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gtamybsjkp.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gtiudlcgib.html

echo $((1 + 2 * 3))
来源：http://dali.jqgfzy.top/Article/details/gtjoxqmrjg.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gtsdsfunjt.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtzcrhnxnx.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtordtvaag.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtfytyqapk.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtfcphrmht.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtspmoerfo.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtoqbaxnmt.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gtcgxusozd.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gthcgvrtrz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtmpcfawyc.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gtapalxrpo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtyhssmpuv.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gtlnemmmgf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtibhxkzld.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gthvpjftiz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtnbblsirh.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtzekwkogv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gtspiwwrfr.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtfcdyajgx.html


<!-- 参考信息 -->