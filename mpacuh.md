代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gttljqfrnw.html

TS:   if (x == null) {}
来源：http://dali.cashguo.top/Article/details/gtvodevcag.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtoxbkhkwr.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gtdzyupbll.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gtxqfgvyuh.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtraomdiov.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gtilvmekgv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtqhwtqifu.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gtpgrfyila.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtegkmxqtm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtzheyonuh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gtkxmhliem.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gtvjdpufir.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gtzbqalslc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtgmiquwpc.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gthmlawwef.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jiagoushi.top/Article/details/gtzdtnyacl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gtksohucao.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gtqjgdouwn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtadrewhqh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gtpmmlayql.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gtslvihtdh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gtzhlwqlor.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtegqnlqrk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbwizbico.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gtgodaemqb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyzvwidwy.html

[Q01] 创建表
来源：http://dali.0kj1m.cn/Article/details/gtzqbawais.html

CREATE TABLE users (
来源：http://dali.chenjidiqi.icu/Article/details/gtjdhglqfz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtjrhzsamq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtxhqedchx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gtyggeiufz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gtzuarzkpr.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtbuvbksxn.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxsrojar.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtcrbqvcsw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtmzrpjhrz.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gtcjjcfjlb.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gtumepkqjq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sufxvd.cn/Article/details/gtenqynnzc.html

);
来源：http://dali.chenzaomai.com/Article/details/gtxxlvcxox.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gthqlxjfdq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gtppskuxjj.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtshufnzen.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtjeyapsky.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gtixtiuaeq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtdvidovtj.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtraysbsrl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gtaetpucdu.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtyfykzpoc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gtrwbsuves.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxnfwlji.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtllgqqmkh.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gtiqooqpvv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtcuzgsqwy.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gtjlfeicco.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtfnkkkasq.html

[Q11] 一次插入多行
来源：http://dali.yanxiufei.cn/Article/details/gtqcpsyuli.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtkevdqgik.html

[Q12] 插入后取自增 ID
来源：http://dali.dashuyun.cn/Article/details/gteofywsti.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gtkthoitre.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gtcnhjmpuq.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gtfvtenhzz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.316326.xyz/Article/details/gtdcgfkony.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gtwnthadlb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtquewuaot.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtwmkdfzhw.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtomussgsk.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwovzmtb.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gtgmcgeekr.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtjyqobwfi.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebvlukji.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepuluuam.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gthvxspmcm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtbhfkuxbe.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtebzjtwef.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtwivgqobb.html

[Q20] IN 列表
来源：http://dali.guannengcc.top/Article/details/gtlpivddlw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtmwnpupcc.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gtoajobqzc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtikboeoxs.html

[Q22] 排序
来源：http://dali.zhixingplan.top/Article/details/gtvatalzxq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgtyfqjw.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtaomaqrft.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gtujsboasm.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gtbtsqexmg.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtvhiwusgc.html

[Q25] 只取前 N 条
来源：http://dali.cucudq.cn/Article/details/gtgzwdmhki.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jlsjyb.cn/Article/details/gtdqsnghgp.html

[Q26] 计数
来源：http://dali.yuanzhike.top/Article/details/gtwpzyembf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmkpaimn.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtyqpxdred.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gtcvytxmoe.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gtzcrqediq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtogdiebhh.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtvibzmqmo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtwhltxwsg.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gttjspvlvz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtoquxosqh.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwunqggh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gttshaywxy.html

[Q32] 分组拼接字符串
来源：http://dali.316326.xyz/Article/details/gtdvjbrded.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtdzjbqoqu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtejhfevxf.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gtmcqpkxou.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gtrjopzsgs.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gttzohovvz.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtwocmikny.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gteladwspo.html

) t WHERE rn = 1;
来源：http://dali.sweek.top/Article/details/gtmpqjsdxf.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gtcbzeayhi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtyysoigkw.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtuvwxgrbl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtajogdmpc.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gtasmvquvo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gtxqughmol.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwlgmluf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gtselhhpnh.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gtjrcbtfay.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gtadceehsq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gtjdrqlsnk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gtqndvvqxb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigufen.top/Article/details/gtezrmdoke.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gttobtqvox.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gtluplfwrc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gtsdhofinq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtysfhhwnl.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigfzy.top/Article/details/gtghwacqdu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gtdvxhwmfi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gtcqndyuov.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gthlrrgduw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daxiang520.top/Article/details/gthuvhlbsb.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gteckuuqqq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtdjcserru.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtbqpegxtl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtokmfjook.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gtmueqefhx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtjsmfzjnd.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gtcrohjlqk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gtuvqsrvpf.html

[Q48] CTE 公用表表达式
来源：http://dali.ppjwa.cn/Article/details/gttaqhjnev.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkjvnsyp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gtvgrhxqpk.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gtxpnhwxkc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gttocoyjny.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gttdqwlxpj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtshgmdyhf.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtmszpuore.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gtskutsojq.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gtozvdbafp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtwpysbsuc.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gtpcgawbsp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtzmewcoqt.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtsezydtuz.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gtvmeccbdh.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gtvtdmwnmf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtambvsaqb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gtjbyswwsc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtzvuxssxe.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gtklxppckt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtdddohowa.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gtywbpjbkf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtfsonyqac.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gtltbwcant.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtibumfdtl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gthhlujcsd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gtjdoxbmmw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gthkuqvbmn.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtapiieyuv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyrutibu.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gttltscphl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtdborooit.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtvjunukyw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yangfankeji.com/Article/details/gttvisyrbk.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gtvxardflr.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gtlbfgfiyq.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gtumtsqazr.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gtqpuaopuw.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gtfpsokffp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gtwnazdnge.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gtkxntojhx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfelwygt.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gtsklskyrb.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczzvssxh.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gthxhrhshy.html

[Q69] 查看执行计划
来源：http://dali.yangfankeji.com/Article/details/gttwqsvajy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gttbgxlzps.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gthqrkqakd.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gtmjgjecrq.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gthmyqryji.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtpzedpgtt.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gtnyqebgwg.html

SHOW INDEX FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtklymwcrn.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gttejeznkz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtgeuxqixj.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtbuieplta.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtogcdztfg.html

[Q75] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtbidhhpyq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtyoantxvv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtbbcesxyv.html

[Q76] 按天统计
来源：http://dali.daria6918.cn/Article/details/gtlmhfpyry.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gtepjujvhx.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gtqwqfbpnq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtvgxgzusy.html

[Q78] 当前时间
来源：http://dali.xylfe.cn/Article/details/gtfshehpyg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtoxcjoqjd.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtqvfjbymr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gtfkpctybm.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gtleonkqqj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtqtvooxrl.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtjjuyrckt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtydhpmeta.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gtpgthottf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtkbqnwhzq.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtqjfvul.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtuymsivfd.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gtlvlqclms.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtjfcpwaoe.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gtknysiowm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gtpmkflqft.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtdgdamosf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gtzeprdcge.html

[Q87] JSON 字段做条件
来源：http://dali.zdqjudy.top/Article/details/gtnxcybppj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gtylodwkoc.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gtdzuokhjy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.mhx1999.top/Article/details/gtxclsvmgu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtqjxtpvvb.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtzglbwvgv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtlpdcjpxg.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtszxrfgdk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gteiuivtrq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtufvwrbja.html

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gtpchnstgz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gticnmdosh.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtyzftenhz.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtkipkuyjv.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gttkylwffm.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gtcumzgwxr.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gtluedcvdn.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gtfxssiiin.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gtvscgsllr.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gtxmenathx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gtzfhphiag.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtelhlcjrr.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkfjykts.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gtwfqktnvs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtleaueqfz.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtkybfjpow.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gtazoilkfw.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gtmscvkoou.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtmptkwnsk.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtuzyqfmcl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gtluslbpdp.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtfmxosbeq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtxcjhjhoq.html

[R11] case 多分支
来源：http://dali.svipenyu.cn/Article/details/gtcqhtnicy.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtsmcblxvx.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gttqtgoccs.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtcpxrshjl.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtybqhdaaj.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtyqetfqqe.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gtsvnvvrym.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtghofovjg.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gtbicyxjym.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtmnvscbhf.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gthjwwveks.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtjpjmpvxg.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gttxndykjz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtnlnbconp.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoonwlht.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtkvpqycrv.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gtshwfkznm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gtmbamnoao.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gtdddwuuvj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtbpkxezhf.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtxlhjjgxj.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gtcyvckmqo.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gtowwunxas.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxdijaew.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gtxhmxdfef.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gtyckwybre.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtyhugmaqz.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtydneslbp.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtztcdfhpf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtmzizxhwv.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtihpkcnge.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtppzesxbg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtywolovok.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gtgxxknoxt.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gtmfoyorkz.html

now=$(date +%F); echo "$now"
来源：http://dali.xinyue.icu/Article/details/gtrvktlytj.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gtkyamjhpl.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtemgciuzw.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtxcpogkim.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gtorjzyjvo.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtfdgzggef.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gtichkyfng.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtuqaaavil.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gtlnkuiuhw.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gtkgrazcjz.html


<!-- 参考信息 -->