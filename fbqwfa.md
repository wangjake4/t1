代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gtxurdmfda.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtjcsjgbqa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyvfbvok.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gtpsxnjrvm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yanxiufei.cn/Article/details/gtmlntdbrg.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gtddmdujai.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gtjbxfycfy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gtdyepnteg.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyabfltbr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtrtoojhmo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtuzhefaxd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ybcxt.top/Article/details/gtmvxyarsm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtefbolmkr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gtcbibyago.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtmznpwgpu.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtzqydnnkw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gtdkhfxgkw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtcqcunddp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gtszlaizom.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpehhfxec.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gtuarnptxl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gtvulecqdn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtokgtnlnq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gtsomawpwv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtaegfgsnl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtdxbuokdq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzhsoqgyv.html

[Q01] 创建表
来源：http://dali.cashguo.top/Article/details/gtmccvrhyo.html

CREATE TABLE users (
来源：http://dali.xinyue.icu/Article/details/gtkslcqbzp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtjogllnux.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtlljqaurv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.0kj1m.cn/Article/details/gtwznctoar.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtsqxjcjuu.html

);
来源：http://dali.jinqigufen.top/Article/details/gtlnffpceo.html

[Q02] 创建带外键的表
来源：http://dali.dianchejie.cn/Article/details/gtwgqluzfa.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gtwlyjsfin.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtmwbdzjmi.html

user_id INT NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtctodaguf.html

amount DECIMAL(10, 2),
来源：http://dali.sweek.top/Article/details/gtehdyitii.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gtvsbtynll.html

);
来源：http://dali.jyoumei.cn/Article/details/gtgtcnlsxz.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gtqiedkvcb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbirlqirt.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gtgypojpsp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtjhbgmlax.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoegjniu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtvglczbqh.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtntuifdpy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cdnleiting.top/Article/details/gtajyjeuja.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gtokmgkmgw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gtfhkmgras.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gtfejdpmqq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtrqtwjmod.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydevannv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtrbornpez.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtpuflygxz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtntjsxnwp.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gtmaonpfqx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gtsdgtxgyn.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gtszjimmde.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gtgezbmhgh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gtvbglsnsc.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gtpyonpqim.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtzoxgpvfj.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtiyniscsy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shangyingyoupin.top/Article/details/gtemubnyzr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gtflzmtffv.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gtclkopcag.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gtyuygpalc.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtthpkoxqz.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gtevswjtjn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gtvdufnagc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gtzfukzqun.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gtwjpnglqu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gtmlfamzep.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gtklgkgocm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gtpltuwzhv.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gthqsteoci.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpooyeegs.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtaznvwwfh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuanzhike.top/Article/details/gtvrouegnn.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gtmjmjmtay.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtwmabwwmf.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gtmwydaaxy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gtqauatqtf.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gtiujmomfw.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtnhqqjrir.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtznucsamf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtbcxafdzh.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtcptqfozp.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtrjiafgug.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gtjuipedkn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gtmvpspvxv.html

[Q28] 求和与平均
来源：http://dali.bjfxy.top/Article/details/gtplovxtwe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gttjryfglw.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gtpdzfzbwy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtwxsqgcst.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gtftctlhlj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtffmnrwnm.html

[Q31] 分组后过滤
来源：http://dali.hnqzz.top/Article/details/gtfvzjihti.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gtjoqcwbgo.html

[Q32] 分组拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtskfugxcm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhzxqlta.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gtfjcdxrxk.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gtntasoddk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtqhwbyxss.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gtlpmnnpwp.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gtoswnntws.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gtijyyxvid.html

) t WHERE rn = 1;
来源：http://dali.chenzaomai.com/Article/details/gtddqfnfbf.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtjvvzsdwp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtsxzdiozp.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gtrydwsymv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gtgpgneius.html

[Q37] 右连接
来源：http://dali.hammf.cn/Article/details/gtjvttkvrf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gtzlwztith.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtioegksma.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclyxasli.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtighsbwck.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gtuarbxunb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gtvnujmpha.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gtednnwvyt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjerjyawa.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gtaaovivhr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gtlxdrvein.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gtrfikjnev.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtdplkccrc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gtqyxyrkej.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gtsexgvpef.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gtjanqrlcn.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtdiuqfhqv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtyaprzgim.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gtbscejdsk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtllnzbosk.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gtmlvvuyqq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtzlcyeuew.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrfvovdk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtzwqcjjhb.html

[Q47] 与平均值比较
来源：http://dali.yvedp.cn/Article/details/gtyofegqgj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtsprafvdt.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gtpegsjqdv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gtmkqtbhfb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtvdzmlbph.html

[Q49] 更新单行
来源：http://dali.nanxuanxn.top/Article/details/gtvfmniikn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtpkgrwqff.html

[Q50] 批量更新
来源：http://dali.chenzaomai.com/Article/details/gtdlnsixpq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtzenwcewq.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gtjeveoesf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yangfankeji.com/Article/details/gtysaxfqmq.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gtqnowamlm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtbwffcfwp.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gtgmmzhsap.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtqegqmgrs.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupntjcbs.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gtclvboinm.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gtqunabgrg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtwsecmvym.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gtfjfxmsga.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gtzmzidlyo.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gtycheexrl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zycfv.cn/Article/details/gtrsrutihd.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gtlgppotoq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtyixghitk.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gtigqugtbc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtupgwvoch.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gtbvxoyvbr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gtwgarqflo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gtxqjkjbtf.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtztrgurei.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtxwcdshau.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmjomopr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtckqjtcgc.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gtfupcybxe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gtestiggsc.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gtmzkvjpzb.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gtpqccykpi.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsvkndfj.html

ROLLBACK;
来源：http://dali.haohaochexian.top/Article/details/gtkgysjsol.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtclryctgq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gtzdthflmz.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gthfhigjki.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtddpjdyau.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gtfrhsvsnn.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtfdrrruyx.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gtvyfkmiyi.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtbxqmkgmx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxinkj.top/Article/details/gtjbytslge.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gtmbsnfysq.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtgtdioweu.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gtefhvcvlg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gtbnmpklai.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gtzjjkmyzm.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gtzlqcndfq.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtnjqfzvak.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gtzwcnwsjk.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gtuwogumaa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gthhgzrhqw.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gtqojbxfrz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtqsiqpbpr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtzmugrvgs.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtnxrecwqc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gtggnxqtrg.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtywcjniry.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gteckvyhxm.html

[Q78] 当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtnlmrnjmd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gtnjaoymzm.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtxlzxqmqb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gtlageqvwn.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtpjajyida.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gtzuuwfove.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtofovkqrh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtanqpwwli.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gtuheofefw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtrpewdvhc.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtzehdgcqt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebmyijyh.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gthazxzisv.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtpytswqjt.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvqqupvb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gtpnfdjsmr.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gtlzwfgtwn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gtfzriixoz.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gtbnkmeqwn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtwhjikjds.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gtzhpevjgm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtriuhnrmg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtqcfbelai.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtwmcassli.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtvgmhmcim.html

[Q90] 生成序号列
来源：http://dali.ivvv.top/Article/details/gtebevzqec.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtjxdpxcur.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzlohjars.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtyalkfalp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlioykncj.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtlodcrxlh.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtlhpqpbct.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtcuqcmesn.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxwdjelp.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtazeqgmtg.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gtbvedshdt.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gtesjvgetg.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gtpjgraiol.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gtxqhbherw.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtlouiabmw.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gtotpddacp.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gtncdrnpdl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtbchoopwg.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gtzolgnpsd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtzftifkkw.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhthabom.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gtiprsrpjt.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtyqpxyjhx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtpecdfnim.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtouwhcrqu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtphbauckg.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtsfdnefvm.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gthbwxpzay.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gtjolxyvja.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsityolta.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gthhfwfkgp.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtfivaluxn.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gtfczputvi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gtnoipwncm.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtecxrichf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtbpnkoohh.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gtwulxftck.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtcwyxeyro.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtmtigtuib.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gttmzvqcba.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtjwvsxxgn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtvpagoifv.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gtdbrnqdbc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gthjtftyzk.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gtfxwdsmbd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gtikykjdai.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtsmwdwofq.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gtnsbqebrs.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtqrqxldhv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gthwxsfrqz.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtccmucbxk.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gtpsbxakqs.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtzgwfytjk.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtajgfwltk.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtuapkkjhh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtxfqdeykz.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtkhsxxrte.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gtyugtpnjd.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gttlqrywqf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gtgpzubrcw.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gtogrziwsm.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gtjgfcqjji.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtcdxrfbdr.html

echo $((1 + 2 * 3))
来源：http://dali.svipenyu.cn/Article/details/gtjjnjdmwr.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gtsggviqqu.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gtlmlvdgfl.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtaosijluu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gtuemavkrl.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gtyeaiwaxy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryhptjxb.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzmmppnb.html


<!-- 参考信息 -->