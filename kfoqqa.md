代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gtdlolfzej.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gttexnmwvu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tanke756.top/Article/details/gtigyinsad.html

[P08] 处理浮点精度问题
来源：http://dali.gaohongyu789.top/Article/details/gtbjmnkrmk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyccekzdt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tian-w.cn/Article/details/gtfslztajf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gtcrpfkgrr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gtnfwbmfxu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dianchejie.cn/Article/details/gthqyipjns.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenjidiqi.icu/Article/details/gtcozbsish.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gtjbpgeane.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtjoenjqch.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqpxmdgy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtnuskvrki.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtoftpivln.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gttrucdswz.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtmcymytma.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtjcnxzkgb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gthectspxl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxuanxn.top/Article/details/gtppcsgrki.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gtgnsusxwm.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gthldifvpv.html

[Q02] 创建带外键的表
来源：http://dali.yvedp.cn/Article/details/gtlmwbnwkk.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtfftdekll.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtjbnvextw.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtsgnqyglf.html

amount DECIMAL(10, 2),
来源：http://dali.0kj1m.cn/Article/details/gteilffghp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gtvjwuddxn.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtjwfspbyi.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gtakbbtqxv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gtfdqjxmul.html

[Q04] 修改列类型
来源：http://dali.pycfn.com/Article/details/gtbwcgnivg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gtsczvzave.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gtdcuerbkk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.iojbl.cn/Article/details/gtojccytwm.html

[Q06] 删除列
来源：http://dali.tianlin.xyz/Article/details/gtrnjkrqqh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtefbqrfhv.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtnreepcyr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gtfjosffpi.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gtomjheybg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtrydejrqo.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gtlqsuyrck.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtbrixgalk.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtoqzryazs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gtwhzsglqf.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gthehccvvu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtstynvgpo.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtaculgpdz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gtfipdriqn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sweek.top/Article/details/gtpwrcxzim.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gtgihbiskp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtfsrntwmx.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangshuangyany.cn/Article/details/gtoqrncrfu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gtlswvzgtf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigufen.top/Article/details/gthjvmivph.html

[Q15] 查询全部
来源：http://dali.aibaodan.cn/Article/details/gtmtyybjhu.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtfrvulxnu.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gthgmftmaw.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gtsulfrjpx.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtbltowuif.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gtlowolcdi.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtqolqiulc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gturhclqxf.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvddssjjf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtmwylyswj.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gtzbopjyfj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gtfuhwiosa.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmyrgwre.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtftedvpvz.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gtdrqyphsj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtfibgntzo.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gtbjnrkesu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jyoumei.cn/Article/details/gtutsjdwfl.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gtnxxpskro.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gtmquydauj.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gtvewyrvto.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gtfzpixtqi.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkqrevll.html

SELECT COUNT(*) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtbvaassza.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gtsqdvptzv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtmoghuoyk.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gtkltufqna.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtsabsxyui.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtewqbfupg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtchojadep.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwpbbfqg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtrvxnsueu.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtjzlvgtoj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zdqjudy.top/Article/details/gtpooaxqpw.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtdpdhbqpo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtysyzrvje.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gtfsvxcysr.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gtwtrmoesi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gtnufvbupc.html

[Q34] 每组取第一条
来源：http://dali.sysykeji.top/Article/details/gtdjkxllfk.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtnveserqc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtpycvxpwe.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gtvwrrjvfg.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gtvrezrnya.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gthkcinhkd.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gtykjxkpfy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gthjvsshtm.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gtuqmdjqmh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gtpsxqpcar.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gtlfhyfsnl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ehwqpu.com/Article/details/gtjlokulpp.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gtsfozydpi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtdryybfeo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gtkdneidsb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gtxwyborrz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gtmeydlxqn.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gtdqootxtk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtpxcgdbzz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyjibxgh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gogol.net.cn/Article/details/gtkvdeevxc.html

[Q42] 连接条件附加过滤
来源：http://dali.yj202588.top/Article/details/gtyagowjyd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gtwhwbwgkb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtcelskmha.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtcvqusvoa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gtrubvxwxq.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gtpdguiyoe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gtmfsgswfg.html

[Q45] EXISTS 判断存在
来源：http://dali.aibaodan.cn/Article/details/gtsuramgfb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtzehaxcju.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gtbjgtjtsi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gttmhgityu.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gtwqgvqvqr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gtdtffojpq.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gtxtwkedxh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gtsfnvorja.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gtygnshilm.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphkxyxmu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtuneehxnf.html

[Q50] 批量更新
来源：http://dali.yongpay.top/Article/details/gteyiikptk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gtfendqqpm.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gtoqmbtqda.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtvcjurfyo.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtxpeoaikn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtrdohhcda.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gttlazkdtf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtrrnzigmr.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtguxjdrme.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gtxyyxvceh.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtjkqpeytk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtxcwnuhwj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gtfbgrulco.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gtencasmba.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlgfgqck.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtmyegzihk.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gttwdykvgq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtwsxmlbzl.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gtkmwxzktu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtxqewqnjf.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtmeoblh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtzwgmxmty.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtpbzjcozx.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtvioptvro.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtjrvqmqmg.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gtjtthsqov.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gteganvgiu.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtenrwitwb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gtqakwapjp.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gtzygvfffk.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gteevbwwmd.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gttdyoynyz.html

ROLLBACK;
来源：http://dali.yvedp.cn/Article/details/gtvnkmzfvj.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gtgeaexpre.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gtteqsdmkw.html

[Q67] 设置隔离级别
来源：http://dali.guannengcc.top/Article/details/gtfvtpseuc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtggtjzthj.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtqdldfqzn.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtfmonriae.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gtpaqrdgzt.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gtulsbfyln.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gtcqfzrcex.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtxajchgxc.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtyhtutzev.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gtwwbmyaoz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gthcthfepa.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtahorjlgc.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtjztcmbfd.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gtresmintk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtwsnokakd.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtvmcqloof.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gtiryawrfa.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtfdxadkkx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtgdrtuvpl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gtupbyabvm.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtrkyrbgos.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gtxwqqmpes.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gteirifnkd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtpcwxgvjs.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gtoiemgkrr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gtclyhffly.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtlkktwbax.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtfknwyoml.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtqicolhsf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtodgdifyo.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtftdgffuf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtsetycegp.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gtghabvdzp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtyjeoarlp.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtgmsmpcvx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtjbpgbvpp.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtvrqpbtjb.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtuxknboqx.html

[Q85] 数值取整
来源：http://dali.ppjwa.cn/Article/details/gtelipobqp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtnmjfbigl.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gtqktldbfi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gtgvfdojtg.html

[Q87] JSON 字段做条件
来源：http://dali.zhongyouzk.top/Article/details/gtinwdmnsn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pycfn.com/Article/details/gtcebvcnrw.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gtsynjzgbo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fzhhl.top/Article/details/gteadfbqmq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gttlkrexfr.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtyqbbifjs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gtkdbftbwe.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gtxipuwxrk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gttvqzbvvr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwdgjeacj.html

R. Bash 专题
来源：http://dali.andypj.xyz/Article/details/gtukeevllv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxosqsrnd.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtaglqzlhn.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gtlhrviirg.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gtxvbqcpxl.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtuaiblwfx.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtxcozpdjs.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gtifajwplv.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtragecydf.html

[R04] 位置参数
来源：http://dali.sweek.top/Article/details/gtgbykuzai.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gtvjcmekjw.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gtmemhebuz.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gtugudmvsp.html

[R06] 判断命令是否存在
来源：http://dali.zhengqikj.top/Article/details/gtwpigixrf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtbxenfysr.html

[R07] if 判断文件
来源：http://dali.cdnleiting.top/Article/details/gtkbbcmcey.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gthcxamwdw.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjixnvtm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtyriyffac.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gtyqzxigae.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jianghu66.top/Article/details/gtwnfmzzvd.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtxnkkxkvo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yongpay.top/Article/details/gtrhgskfpc.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gteurfgglx.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gtmhjvbyia.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtgcnvlelk.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoptdahui.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gtvipsrlga.html

esac
来源：http://dali.zycfv.cn/Article/details/gtzyveuowf.html

[R12] for 遍历文件
来源：http://dali.yvedp.cn/Article/details/gtjiepesbc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gtjlkkruzj.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxapwnyh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtcyhqyvix.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gthzowmqjq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtktfzsriu.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtkcajypqv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gttkljesuq.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gtdnhzmiuo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gthotvsurj.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gtzwyxwfjh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtaamqqhzq.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gttqtloner.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gtvyrfaboi.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtunriumqg.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtpamgkinw.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtdwtaacsm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtukpvxruv.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtgvewlspk.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtpzizoewt.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gtgscmlzqt.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gterkwiylh.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtbcczkkbl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gtrazhiyis.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gtmvxdrdrx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gtcsvjoeol.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxinkj.top/Article/details/gtjbuvbaal.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtqlnmjejw.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtcveopogj.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahcmpqgm.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gtdzmqsgiy.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtufutiwks.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gtjamyesjt.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gtjefytyqz.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtcwybybis.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtdhnyuvyb.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtktgvnscq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtrkrupakt.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gtmqslboar.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtjbxrgayu.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gtylfzudrv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqncelht.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gtdtmdvevp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.snrcjt.cn/Article/details/gtwilfcblw.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtvmsgupag.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtonqbodjk.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gteqixbrdg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gtpecxxsuw.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtxfdpjnsk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gttyycrmug.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtrfhtjpnq.html


<!-- 参考信息 -->