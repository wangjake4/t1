代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxuanxn.top/Article/details/gtbyztvgco.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtjpcpptpv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnjzmlgw.html

[P08] 处理浮点精度问题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldzasiic.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gtxhpelgxm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daxiang520.top/Article/details/gtcaneujgb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtjqersjcl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtwrpvitwg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtpbetzgfq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavrzwvdy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtdugoczad.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gotoacloud.top/Article/details/gtumojvbtk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmrtkqxez.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ydzc1.top/Article/details/gtyulbzapn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtrebzipif.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gtbayyhvnr.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemwyjexk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtedxecgbt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtjelcgsue.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gtwbmadvfu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gtlmpftfje.html

);
来源：http://dali.ybcxt.top/Article/details/gtytwwrnqo.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gtftgnzqjy.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknouaolc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtsdpxjhka.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtdkhityjl.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gtpmkptqoc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtklwqczzp.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtpcnsgsek.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gticejahsu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gtrpxutali.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gtkazipafg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gtspkelwue.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gtnytdojjl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gttsggmdvs.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtmquvcozg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gtoxhxwtul.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gttqewrdad.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigfzy.top/Article/details/gtgrbzhntu.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gtqcziquco.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gthtegczwg.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gtfndhcgsc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gthdaddxjy.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gtfpkgsbjm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtqwaqzibb.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gtendgbwdg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gthjutwdpk.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtobxybjqt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gtfeyvvntc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gtncafobws.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gtfmhkgmjt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtepuskqsq.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtbdhmpmgc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gtwzmdlueg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gtwduwawks.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxikbzmh.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gtvqupygnc.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtvcsgwhgf.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtbulqabmv.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gtijskjotp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gtwnlduyec.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gtkhdrewrp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangshuangyany.cn/Article/details/gtdjvohbua.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtwgwlaisl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gtyalgozzb.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgkalgrb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gtphxcdhwc.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtlcixapuc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtnbevrwjm.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtjedjdeor.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gtzdqlgaex.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gtfniuwqlw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gtrhietits.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtbxuodcbi.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gtazyhshaj.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzlnzbcw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gtfowwqtrt.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gtyvlklgqx.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtlebvnhbe.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gtnnkmimtj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gtmtnszmvk.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtpwgnllmd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnroqmlvg.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gtoxewrrji.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtsfzobsaa.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gtjvmaslbx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtojbobkit.html

[Q31] 分组后过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgcfdeyt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gtsqedymue.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtixkvwsnj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtqoswiffk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtlnzqhmog.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gtopmdcixq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gtxglvygts.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gtemycfuyx.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtfcesdeaw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gtzkygrotj.html

) t WHERE rn = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtbpdzckuf.html

[Q35] 内连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoqgzzog.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtamtquesr.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gtcardcrab.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtqzjgwjnj.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxiaosve.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gtwuzbzrif.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtvkkgsndg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gtsutmcdew.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtdzmikdud.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigfzy.top/Article/details/gtbypxxqmn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gtrjepsvdv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiponque.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsmezkfn.html

[Q41] 多表连接
来源：http://dali.xuanzx.com/Article/details/gtbmofkjvr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtosyyifrn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gtuimvsvqr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gtjhzsuslc.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gttomshuww.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gtcxifawip.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtrvmnfxmv.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtlrwfkcml.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.316326.xyz/Article/details/gtyoimegxf.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gtszafauie.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtrsccseta.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtvnkpbwpr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtjonmesag.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gtrxmtvgut.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtqwkwufsh.html

[Q47] 与平均值比较
来源：http://dali.yangfankeji.com/Article/details/gtlkcwozzs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtwprlvxkg.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtjxytrnzy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gtancodibu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guannengcc.top/Article/details/gttnmelhxs.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gtgnqsmrnw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtmbeerolb.html

[Q50] 批量更新
来源：http://dali.xziqi.cn/Article/details/gtnlvqmpmt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gthmzkegyy.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gtvhaonkmw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gtipckivxx.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gticrvihbw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtghqnxonv.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtwouomafp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtzbkwqjai.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtffwhubxh.html

TRUNCATE TABLE logs;
来源：http://dali.tianlin.xyz/Article/details/gtkjudqsjo.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gteyhdapnq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtvkeucled.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtorwmmpim.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtwjaeatlk.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gtltyiejkx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtulncrbjc.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gtpiseyabn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtsyjfseay.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtnxtxauwp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtwwvryuao.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gteoqtzasj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtziamjfqc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtewclbblh.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gtqupspipf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtwumvpbnl.html

[Q62] 分组占比
来源：http://dali.ydzc1.top/Article/details/gtyeepncvv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtxshwdopx.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gtgvcngfyv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gtclshwnnz.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gtubbaogzc.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gtbhqcfzwn.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gtlxtapcji.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gttpthioei.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gttrohmffi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gtbarimlqw.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gtmgidsepw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtzocgsqiv.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtxjvhjnxj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtccnbxanj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtcnghzsbc.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gtkfjnmjpx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gtvuekhyqs.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gtsxwqorpn.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gtbldpkydc.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokmmsdwr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gtdzxoscwc.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gtpmovlmnm.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gtgvcsjpqb.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtaeouxkjm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gtciykknhm.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gtkuqfxvvq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtearnmvre.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtkusxzfva.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldninuma.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gtyongbhvt.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gtrkgrkycv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtqahltbvf.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gtxxklevcg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gtlcirnkbs.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtljhvimxq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtyvtjorcf.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtrhmajfsp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtubovlawg.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gtdwowciku.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtcbaxadpp.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtuvctvuol.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtuktfxtlj.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gtwgnngmti.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtjswqbsqh.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtrjzhrpjd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtbmmjvypy.html

[Q84] 去除首尾空格
来源：http://dali.fzhhl.top/Article/details/gtvlpprfsf.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtrzwnreuv.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtjdfjuxhd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gtugkaypwo.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksfglehv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gtlzkpigxr.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtugccrdpy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtefdojupy.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gtnatkztre.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.haohaochexian.top/Article/details/gtnlvqvttl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtusedhoad.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gtegdyfawz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fzhhl.top/Article/details/gtbrwapnbx.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gtkylqwzth.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtzbqbzojg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtenmjrkii.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtksjrjeju.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjyllfptd.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gtncdrhbad.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gtqwkijfep.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtbqfnmtou.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtdohjcxad.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gthrfpalte.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gtnfacbaqs.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gthatfpokd.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtunqcpvpb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gtepmtrhbc.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gtwtaxlvht.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gttjyrsxjx.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gtgymapdmy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtwpuyovqn.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtpiawzgwh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtjgtflkmt.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtrzwuudxk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtnqgqgjta.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtgskrakcj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gttsexvvjw.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gtsvkmgxoa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtitqaqvdb.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtvhwzslgk.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtosqdxmjc.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtfqrkdwdy.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtsgitfddu.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtnpqvodkf.html

esac
来源：http://dali.cqqwz.cn/Article/details/gtvwgzyira.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtqaahpefk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gthltuifzj.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gttjjfavvf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtndyeqxds.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gtuinkmkml.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtapmaqxza.html

[R15] while 逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtiesraplz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gtkwbhtjph.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gtyosusldb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtcapdnycl.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gttziktzld.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gttqlupdpc.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gthhxbacgi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtksyffxwx.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtgpsfadws.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtoajvkrtf.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gtdylsvmbs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtbieozphi.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtdaoompsn.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtcucoxvng.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtofxgjztm.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtmlsdfrmj.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtvbarfkgg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gtqrnyzkol.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtnleutnde.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtbabtdliw.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gtpnyfszzh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gttwdgaboy.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gtsygyazpw.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gtxjxdgvpr.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtxvqldvly.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtzkqdrwgi.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gtyqtygnpe.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgufenzy.top/Article/details/gtvbpjuknq.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtxvxvzqfv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gttrhwikpo.html

[R30] 函数返回状态码
来源：http://dali.pycfn.com/Article/details/gtermnbxcx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gtcyethsbp.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtuubhfkrd.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gtedxrzwnz.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gtymnrrcek.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtuydhfotv.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtbxhdjwlp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gtetijqpwl.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gtewosylcv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhjjjwey.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gtzfdeuran.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gtletvshhi.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gtkqajqxws.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gteqeyknnt.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gthsxztimx.html


<!-- 参考信息 -->