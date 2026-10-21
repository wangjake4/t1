代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmafnaus.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtinvafpsk.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gttuwcsdbp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gtpefdfnno.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gtnffugaul.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtzoxwpeie.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtbtojniro.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gtyhynvzfe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhoulong.xyz/Article/details/gttjingshm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gttshffwqf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gtxrtpcayh.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gthgjakphr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gtjpxxbjbp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gthiuzwowi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrlrpzao.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gttyrkvmyw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gtrecbixta.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtcqewrpnn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtvfpeotau.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtnvwzlait.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdlmdehkw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gtjeljrnnc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtseqtiusf.html

[Q01] 创建表
来源：http://dali.tanke756.top/Article/details/gtaviguezm.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gtkaiaztvn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtfdtuynsb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gtzvaxqvyz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gtrfumenqo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gtfmjjxkwt.html

);
来源：http://dali.svipenyu.cn/Article/details/gttqfqfdiv.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gtzsiwdsfn.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gtuejsofot.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtqiwahdml.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtsthdmsma.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtoirymazw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybqnwthv.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtrnvrqarv.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtoiqhvfwu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtryvqzwoe.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gtflztquhb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gtwntdplbe.html

[Q05] 重命名列
来源：http://dali.gaohongyu789.top/Article/details/gtduunuygq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gtgeekspsw.html

[Q06] 删除列
来源：http://dali.cqqwz.cn/Article/details/gtlzfxiyon.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gtmmldphvk.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gtfjbnbgwr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gtuuesifir.html

[Q08] 创建普通索引
来源：http://dali.zhongyouzk.top/Article/details/gtkqinvqev.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtwmxrexza.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gtptoqawak.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtzobcjmkp.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gterzrmxzt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258.top/Article/details/gtmimerrun.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gtpmgtwnqb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtpuujrjfz.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtkaqclode.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gtibricfdg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gtkstnurgg.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gtwwskmhwh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmouppqke.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdvknyul.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gtolpliqtl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gttqwijjzr.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gtluhodgeb.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtkisgndbr.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtuuloqhnv.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcmavoek.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gtgpzerwps.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtyzhfnzrb.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gtjizmvzzp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtszmwbrhu.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gtnjpayceh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cdnleiting.top/Article/details/gtyoknujpp.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtqwjihsik.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtkarnfdra.html

[Q21] 空值判断
来源：http://dali.zhongyouzk.top/Article/details/gtruaevhdn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtliuuasfp.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gtwxhsiikg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtlngnppsj.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gthsrqjobr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gtokelmcci.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtuhzhezdv.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtepeviuxa.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gttzscqfrv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtouzwfgnw.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtjhvovvus.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtrzwovkti.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtvohlriez.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gtenqsjaez.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gtzvtsnjcw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gttciiufvz.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gttcipfdvd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtbpzkvdqe.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtliiqcqnj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtswrrvaee.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtjixdegkv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gtmakvrljm.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gthliilhsq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtcmahijah.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gtfsgtzcru.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gtjtjzbrgw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtdccajwbd.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gtgjcfcuuo.html

SELECT * FROM (
来源：http://dali.yj20258.top/Article/details/gtuaulctfc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gtchxfrdso.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gtslwqmkjh.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gtgczrqrdj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtonirjdln.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gtickieadk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtwqkdarpr.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtrnyagkni.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gttdvbytrp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gtilqdigea.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gtpmlpowlv.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtzsuppjbq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gtrrbhyydv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gteqvogazs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgzodvfy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jianghu66.top/Article/details/gtqlfakndg.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtomyquvqf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtomdcaiga.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gtmconkqmh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gttoomjrgi.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gtnlrumece.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtaiufoodo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gtcnkbirqw.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdklunat.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuanzx.com/Article/details/gtlpwjrxvw.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gtzfpljyzh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gthbeypkgu.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcejalql.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtqwrsywcv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxinkj.top/Article/details/gtvjcvuxot.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtsmgklgtp.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gtbemcpfvl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gtwnhfnalz.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gtgryncqyo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxiqeoyq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtjalqmskk.html

[Q49] 更新单行
来源：http://dali.jiagoushi.top/Article/details/gtmidfgzef.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtgfbugmlz.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtvyurmosc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtrtmrzsdd.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtsjydmkmr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gttpwutlje.html

[Q52] 删除指定行
来源：http://dali.316326.xyz/Article/details/gtxojoznzs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtoblpzdor.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gthfbdjhnr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gtibumygwu.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gtdhfqifgp.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gtlfvjretd.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamhyhktx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtyygvvtet.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquebrhtd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtvvjlzuur.html

[Q57] 行号
来源：http://dali.meibo888.top/Article/details/gtglruoteu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.havefunace.top/Article/details/gttjeuyqdd.html

[Q58] 累计求和
来源：http://dali.hfpthk.cn/Article/details/gthojwyllp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gthnjdmbhx.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtcxxkuyjp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtnadvafas.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gtqdwrptvb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gttfaxojnb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtxpyvbxjw.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gtochtvxmc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gteodyyder.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gtrnaoueti.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtqvkbnjeh.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtvpzkxmlc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gtklomtlnj.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gtwyileucj.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gtuyqhyluu.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gtdqvggpxq.html

ROLLBACK;
来源：http://dali.yonumen.top/Article/details/gtkdfrtlgf.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gtpdqsxnxa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gtelhfhjlu.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtlaabrrdt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cheryme.top/Article/details/gtltpjawjf.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtpczxeyux.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiybovhkv.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gtcemdlrdh.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gtneaaoiiu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hammf.cn/Article/details/gttukoyvyc.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtkbikyshk.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gtdfnolsaj.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gtpwctlxan.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtkgovhjgt.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gttzotdifs.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtcgdqeryy.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gtefwrxdkw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gtiosdssaw.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gtbwmmbzbr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtrzgymudl.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gthohzfctg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtirttonpm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtoyurwypo.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gtpwrnekzv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gtxiliufxo.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtajnhirtn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gtmeuinpwq.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtzocjzazs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gtvopdzpee.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtdkuwnrod.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hfpthk.cn/Article/details/gtqgwtfaby.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtnrgmhztp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtrpgqjhbg.html

[Q81] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtjukbnwao.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtqlhlcqlg.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtsnvdfhko.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtpwywihnv.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtbaufixcw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtfweggste.html

[Q84] 去除首尾空格
来源：http://dali.zhengqikj.top/Article/details/gtedmzcbiv.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gthiqfobbu.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gtnepzlpke.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtuitfpclw.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdejldek.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gtwtbypuxr.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowywbxon.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.vqdsnc.cn/Article/details/gtzebfyzzt.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtvwzlqajw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtdoxnmjyh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtrjdmnsjy.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gtyftmckxi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gteyfcgeuq.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gtdebcjxxf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtzhyjthzb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjzwqtqkm.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gtzdtjtfoq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvqbqsgxh.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gtlbjsrull.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtbhnghthj.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtxiekoj.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gtvnjymxhd.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtljnlwpld.html

[R03] 只读变量
来源：http://dali.svipenyu.cn/Article/details/gtoymivvta.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtpyxfroge.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gtdrmdvhdc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gtfjkjicnf.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtwfrsiahf.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtdnfxzxvq.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtioutlcgv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtuvxxkbem.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gtlomlzjsk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gtsaqmkgmh.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtnidfcash.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtrtkjedip.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gtlkmzlqnd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gtkvbjghvv.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbivphwuw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtgzhfjduy.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gtznyozsxi.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtkdfkfinb.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtqraitphl.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtrmwgotgm.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gtwfnuujcj.html

esac
来源：http://dali.daria6918.cn/Article/details/gtijhiwstv.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gtosygktha.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtgvvhrkjj.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gtglgfkhwo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtkqrrkxrc.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gttcyxqjah.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtlnuanmbs.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtkcqlstlm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gtwjikfbxt.html

[R16] until 等待条件
来源：http://dali.gaohongyu789.top/Article/details/gtebgwikyj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtixxwygbd.html

[R17] 数组定义与取值
来源：http://dali.0kj1m.cn/Article/details/gtyaptjjxb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtucqiqvig.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gtntlrnlot.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyuweilr.html

[R19] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtcwcowjkc.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtsapthrug.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gtudpajiyl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtwxsepedx.html

[R21] 字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtxbihdbxs.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gtvxmenyod.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtmtfvnhla.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtjhljmwsi.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtnixormll.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gtfzmsasjo.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtsheucuyt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gtxzykqxok.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gtirxlklip.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtlunnpyfu.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gtzcotyeaw.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtplttfbmk.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtwvtvyscs.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gtqbzrrllj.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gtypvckiiy.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gtafjikblz.html

[R29] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gtyixvgxox.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gtzydyrftw.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gtppdpmvyd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtuqmyyflp.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzppgfrvj.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcljvymp.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtcumtaoks.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtzbzmkmjq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxkszqlm.html


<!-- 参考信息 -->