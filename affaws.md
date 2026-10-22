代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtjznrkacg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtuciipfoy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gtbonirwip.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtlzjazlaz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jyoumei.cn/Article/details/gtqiaszvpf.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gtvuehtjpj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtojkpqsav.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gtrjhuifnj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtxrbjplfb.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gtfkvlqbyf.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gtlcdbmjvx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gtcumljixf.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gthifoimtr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtxkxdohtj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtyfymzkqt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiwqbpxi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gtyigyecdw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gtyizaoldt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yanxiufei.cn/Article/details/gtbudlzaww.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gttnozwvrh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtkahuhyvg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtmtyhjqmw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtvcimllim.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gttvppvnbl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtswtfgcsd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gtuklytpze.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gtnsetwpfn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gtsnpogjdb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtsviatxwt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xinyue.icu/Article/details/gtmuwydlkg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkoxbjmwk.html

[Q01] 创建表
来源：http://dali.jqgufenzy.top/Article/details/gtutafpkpq.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gtgwhnliep.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtfihmngmi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvveeeqvv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.0kj1m.cn/Article/details/gtahcpdqin.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gtgfdshedv.html

);
来源：http://dali.jqgfzy.top/Article/details/gtvqtxmljz.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gtvoduplht.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtaiublhot.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtvtkjmejo.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtvgvhzktb.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtkjtyjymb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.316326.xyz/Article/details/gtnonapsxt.html

);
来源：http://dali.cqqwz.cn/Article/details/gtemgqdlmd.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gtrkkljtwq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gtmgyaopvl.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtgcuuzutt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtuxlnjrgj.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsbmqnkt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gtcxcbzvft.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gtgnswwqzx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gtmslrjesb.html

[Q07] 删除表
来源：http://dali.andypj.xyz/Article/details/gtrbhsrmua.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gtjrymholx.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gtwcgrtpek.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtzxyrqagn.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdqgptck.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtyuvpkccp.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gtnqmywbiq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtngyryhld.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtjsbhslzj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtyaeojxox.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigfzy.top/Article/details/gtnuvpuant.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtplvegiuc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gtdmgoqjpd.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gteknelzee.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtzdqqgmmq.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gtdxlzhvgx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gtpqjiepyu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gtrjtaslou.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtxrudwpis.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gtocluwgmq.html

[Q16] 查询指定列
来源：http://dali.zhongyouzk.top/Article/details/gtxnxywros.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gtxwrbgbfw.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gtlcksirlz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjochmpeq.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gtkzcqnymk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gtrlaevimp.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtnulcjnyr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtjkorwbtp.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtypevzvql.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gttfsfzwfx.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gtxbhywlqx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtpkqvguvt.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gtzmufkosp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gtqdinauhu.html

[Q23] 分页
来源：http://dali.sufxvd.cn/Article/details/gtnavnsvsq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtvpzfggwr.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gtoqrytauv.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtxhfpzgvm.html

[Q25] 只取前 N 条
来源：http://dali.ppjwa.cn/Article/details/gtasslqgeq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gtftwrvggm.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gtgypvgmcv.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtnfxsdgyp.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gtdvcxgorm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sysykeji.top/Article/details/gtbgdaoynx.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gtjlzcioti.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtpvttszul.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtvvglvbjs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gttdporzzl.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtgfbibntj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtlskbuxej.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gtewkigaqs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gtqjlesdeg.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtrprvkihy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gttzmpghrz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gtqszpmxof.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtokpanbfa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtlnynvtis.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gtavorldgk.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtdiwjxxnk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtwebwjtrj.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmktzltv.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gttqemocki.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtnfjaddlu.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gtwcljpimf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcfsennk.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gtbyqlttiq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtlttzjbky.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gthaimsprm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtympjbpjt.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtecycsxor.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gtjvmpnftg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gthswoyuoe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gtadzowsrp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gtnmagxiae.html

[Q41] 多表连接
来源：http://dali.nanxinkj.top/Article/details/gtjhsabamy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcjkfagc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gtjlefiyuy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtmnuddjpq.html

[Q42] 连接条件附加过滤
来源：http://dali.dashuyun.cn/Article/details/gtqpchrisp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtquyannup.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gtxnpnnmau.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtruwdwrhv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gtfvvmloja.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtibbrekgk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.redwolf501.top/Article/details/gtqlrixbei.html

[Q45] EXISTS 判断存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsazrrkgg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtiapfnjmz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gtifemgxgf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtrunksrfp.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtuanqbaym.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtwopstahc.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gtasqlyrcq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtuclgttcy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrfkrstn.html

[Q49] 更新单行
来源：http://dali.yj20258.top/Article/details/gtiqrcixnq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtamlxjkdh.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkjhshdr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gtitnqirbg.html

[Q51] 用子查询更新
来源：http://dali.yuxming.cn/Article/details/gttoxjmadm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gtlmsympqw.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gtlrcirrum.html

DELETE FROM users WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtlemyilru.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvifjdqn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtiprldhyv.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gtrabgpqtf.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gttkqohzbk.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtwsumlsye.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtnxcuwpcu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.bjfxy.top/Article/details/gtxropozkl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtybidsxrm.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gtafhukcgd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtzbsyrstm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gtbytosals.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtwphrqtnh.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gtcqisulik.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtlsrqeckl.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtblijznce.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtuyiawpga.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gttvxvcrqc.html

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gtbtbzjrhb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtlvdkiwpz.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtwjlmaadq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtpivjjsej.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtjhjbbwlx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gtzmfnjdmc.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmztubewe.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gtzvxnxbxh.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gtlwyyymal.html

ROLLBACK;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxrzfkfx.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gtathvblzr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gtnuaslqpx.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtysfzsbqd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtjxxdtcss.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gttilazzwy.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtdjbbnnsa.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gtuvbdnlbq.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gtrprsgfto.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gtiedkpbez.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepyifgbl.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtwdouvjof.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gtfluynmdv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gtbsagleow.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtcqgyntpi.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjzccznud.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gtkqlzyvsr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.haohaochexian.top/Article/details/gtjasvbsbx.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gtpcrpezqb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gtvuexckuo.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtmhsupzms.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gthnefbuov.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gtssuzktop.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtfoquxass.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gtjxbowvtz.html

[Q77] 时间加减
来源：http://dali.aizwys.cn/Article/details/gtbjruvyvd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gtlhgkhdov.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtljonqbom.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gtdtlchklm.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtdobenixo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtyxcqyxvz.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gtzuketanr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtavnughjp.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gturntrbzx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gtnjytzsof.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gtokiwuksc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtyyxjfqno.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtopiwmceu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtinptzqmx.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfukmcshm.html

SELECT TRIM(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtjzmbuzdo.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtfelmunzk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gtvykwambc.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gtpmcauqio.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gtfpzoavno.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtyngeceyk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gthqdrccmx.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gtdxvazcdm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtjwtfbxzu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtvrocvodh.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gthiawkimn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtkouvzdhb.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvbxbccy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gtaodjofsb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtryhcbtoa.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvaqlgei.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbvyecdvv.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnlpmxbx.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gtrjevtncx.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwxkhujr.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtncvvvtvd.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtynbhvcnw.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gtafxktzxq.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gtnhezcdss.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gtpjeqikyz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gttqwagplp.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gtwmgqslrb.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqszgycny.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtnqzmllsv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtarnovhhc.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtovzbihzc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtxkqsecah.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gtsehwbkwj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtutlezrco.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtpwtgemjs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtdmyifseq.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtnfzwvtxa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gtpozonloh.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gtpjrkuhjd.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gtfherkktv.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtajqofbyu.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gtqhxicdxz.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtcluiqmkh.html

esac
来源：http://dali.xylfe.cn/Article/details/gtlzfqeltr.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gtmybbcwps.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtlyuhsfzq.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtfzkzmtud.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gttnvpqvxt.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtjcffoqai.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtzaeshvqr.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gthozgeitv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtamkyrwjf.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gtfomibxyw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gthywchgjj.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtzfpqhigb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbpxsjed.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtfjfilpyi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtjkzkqlvh.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtfzmbicwg.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gtsxckoguh.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwpqookc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzqljejn.html

[R21] 字符串长度
来源：http://dali.sysykeji.top/Article/details/gtmhthetxn.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gtlgtcpxpe.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gttlzmmvxg.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gtakueemze.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtuowwuxsu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gtrltkpomq.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtrdympkmi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gtsqfrkmqw.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvstjfacv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gtbngemtvy.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtdexeokho.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gtuxgmarre.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gtkevsexjk.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtciwqcavt.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gtsdrfcohz.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtywhfkwxh.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtpvizgaru.html


<!-- 参考信息 -->