代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gtkrlwaprv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtjjxbucdf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gtinjcpulh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gtkmuwxvox.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtkjcurytv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gthnqijuiv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gtaksmqtey.html

Ruby: a == b
来源：http://dali.gogol.net.cn/Article/details/gtbpfcxumr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjgnwogi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtwvlpvjzo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cashguo.top/Article/details/gtrmidrcga.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gtneyncyba.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gtkahoszdx.html

TS:   if (x == null) {}
来源：http://dali.daxiang520.top/Article/details/gtkanpomvd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtrbzdyeha.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdhhdkzi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtrxmqohlm.html

C#:   if (x is null) {}
来源：http://dali.pycfn.com/Article/details/gtkbutslkq.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gtwztkexeb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hysaishi.cn/Article/details/gtrvectgsv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gtpxnqhpok.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiidyhgi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtsjxtmbvn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxkubkfnu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gtmnobnqex.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtbsyevjte.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtlhtdkizv.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtmxevinyu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtuipsnyin.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuxming.cn/Article/details/gtqhjsbeco.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtxjxgxwog.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gtghoveytr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gtaehqjkxt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gtywuaakmj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gttzfvzott.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gtkfvxfrch.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsaktotus.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtwewyfwlo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtabvrzyhl.html

[Q01] 创建表
来源：http://dali.tanke756.top/Article/details/gtgohahowe.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gtwbndprde.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtrinwovcz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtonotnczy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gttlpgnzqz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtyrzuvsdy.html

);
来源：http://dali.yj20258.top/Article/details/gtaacklvvk.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gteqqoxpgz.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gtmnrcxbvc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtnbotcfhb.html

user_id INT NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtjtkcmnyc.html

amount DECIMAL(10, 2),
来源：http://dali.birdmap.top/Article/details/gtnvcinwsf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gtksertuzl.html

);
来源：http://dali.ppjwa.cn/Article/details/gtmxcrmpcz.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtnsjjmkos.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gtstljedme.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gttuxkqqrb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gtjqbnjahx.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtkrdxwkmo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gttmqbdpib.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtsfwkevty.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gthkdmnpsl.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtdeozrzsn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gtzxaihoqo.html

[Q08] 创建普通索引
来源：http://dali.ybcxt.top/Article/details/gtpxwwbmvi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtwifjjktn.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gtjqpurkpz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtjhouldwt.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gtdbtkpziv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gtwlpvuezg.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gtjfootxtw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gtdnxlrios.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gtzpducuqr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gtmuuqlblk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gtndybbrpf.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gtkasoigds.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.smart0.xyz/Article/details/gthvmugltr.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtpkezbhyx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtwgugllyz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gturfxyvzo.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gtfeztvfwo.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gteyljbfmn.html

[Q16] 查询指定列
来源：http://dali.xuanzx.com/Article/details/gtnhftemmo.html

SELECT id, name FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtpgbijvlp.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gtxncdycgs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gtyzzbpklk.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtluolekbi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gtkvehbqvl.html

[Q19] 范围查询
来源：http://dali.shuidangran.top/Article/details/gteykxlcez.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtncehkrgt.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtldjdqihn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtawzslume.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gtvuvvfwyh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gtnnetirmz.html

[Q22] 排序
来源：http://dali.yj20258888.top/Article/details/gtjowykdpn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gtxmpzuoyu.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtyrbajlfp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtdqzxtrrw.html

[Q24] 去重
来源：http://dali.sxryk.cn/Article/details/gtyquwpzjk.html

SELECT DISTINCT city FROM users;
来源：http://dali.havefunace.top/Article/details/gtprfwewma.html

[Q25] 只取前 N 条
来源：http://dali.ivvv.top/Article/details/gtnwjwcyhg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jlsjyb.cn/Article/details/gtibnpcsnd.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gtgudbwrgi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtjddgtmmv.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhfvyrxi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtodridpyi.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gtgptbbnqv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtjcqrzzgt.html

[Q29] 最大最小值
来源：http://dali.haohaochexian.top/Article/details/gtytpxaijl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gtfkydqvjn.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gtmftwfebw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtnzckuuyx.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtezskyuac.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gtsikzpsdn.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtpqekxfmv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtnhquuwqp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gtsnzodsrw.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gtgyjrtxzm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gtcvdhlnyc.html

[Q34] 每组取第一条
来源：http://dali.yj20258888.top/Article/details/gtyzkboqoh.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gteihlruia.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cucudq.cn/Article/details/gtswweiaqu.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gtmikqsmpb.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gtntphjtan.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtzxyywwkn.html

[Q36] 左连接
来源：http://dali.yj202588.top/Article/details/gtakwacybc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtoupcynym.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gtibgistqr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtjhwhfymr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tanke756.top/Article/details/gtovegwvme.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtfttakzxy.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gtdpmyuomy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gtrhlbjwhk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtuipkplek.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gtbaeqkkef.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gtwppkuecd.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gtizekqgoe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtmumlmouj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pengpengdd.cyou/Article/details/gtfgegsqsw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangdashe.top/Article/details/gttarkjqgt.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gtyyvnduvv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gtphxnmizf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtjxadkkrl.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gtutnyjstj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtistcdygs.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gtnhkjqeel.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtnndlcbor.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtcoxeopwh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtqabpxzzu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cashguo.top/Article/details/gtfppocucj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtcwvdwapu.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtbvildwfq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gthaqdgqra.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gtrhtljruj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gtzcpturud.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shuidangran.top/Article/details/gtthawwoyw.html

[Q49] 更新单行
来源：http://dali.guowangkeji.top/Article/details/gtdlqapazv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtvzqtvwjd.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gtmaapjges.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gteuqmkswg.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gtbimhtnae.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtwyyjultg.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gtploqsyvu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtgcdhfyte.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtwhgybqbk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtcfqstqct.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gtqftpvjea.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gtytmvdhhi.html

[Q55] 排名（并列占位）
来源：http://dali.sufxvd.cn/Article/details/gthsqdgfyi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnfckurh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtplgoqvez.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtqlflmdpj.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtsybzppzj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtnasnkglf.html

[Q58] 累计求和
来源：http://dali.xuetiantiany.cn/Article/details/gtjlinzblz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtiictjrfe.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gtgxnhecms.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtstjbuuzl.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gtzqockyxu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtndnvshdd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtnqberuxd.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gtezlfdopj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtvjqbrslc.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gtrswgpler.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtdaqealzc.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtvtielqvh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gtrofbhwcu.html

[Q64] 提交事务
来源：http://dali.svipenyu.cn/Article/details/gtylyvbjfb.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gtruktgakw.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gtbfohyknb.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtuwdpkfuw.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtwewzgren.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgufenzy.top/Article/details/gtiafchqiq.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gtaqqccoox.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtlolkgkpu.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtlxjouecz.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gtjhxlubul.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtqmvmgeoz.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gtuxtbpgfe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gtkgijtfmf.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtdeckczmx.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gtlzbcvcjc.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gtpcwytrmv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtacwwrpkm.html

[Q72] 查看索引
来源：http://dali.birdmap.top/Article/details/gtlectafdm.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtvnziwysq.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gticelmemy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gtwrllumzk.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtqlvtedig.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gtyjdpslly.html

[Q75] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtjcyjwxrt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtwfcktljz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtlclzqecj.html

[Q76] 按天统计
来源：http://dali.iojbl.cn/Article/details/gtumavyzbe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ehwqpu.com/Article/details/gtnmmrzlhc.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gtevibbexp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gtazvfeamw.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtbxamaafs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtcmvqykmc.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtbtaroexu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gtkyvvodyo.html

[Q80] 字符串截取
来源：http://dali.yonumen.top/Article/details/gtsgaycjgf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtakqzmwok.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtsthaohdt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtqsdpumxe.html

[Q82] 字符长度与字节长度
来源：http://dali.zhixingplan.top/Article/details/gtdhnrrncp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtgkfrvzwb.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtrlnqqzvb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtpklewuwy.html

[Q84] 去除首尾空格
来源：http://dali.c1oappe.top/Article/details/gtkzpvubur.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtuegmsseg.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtpewsayfb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gtxscaqbjg.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtauwmeuvk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtevrvhoub.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtvpptgose.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gtlowqqbwh.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gtjhnqrsyz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gteqbiurnp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtqwidhkiw.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gtzfwrguvh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gtkqazchnt.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtrtfssiqi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gtqpiatxpc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdtuhqpzd.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gtebxjocze.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzifvcugx.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gttxxryrnz.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gtthedmvro.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gtmjieoemt.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtetiqilon.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gterpqgzwi.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtcihlekuq.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtjwmbtfgu.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gttpbsychq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtgtwzhpll.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gtcvnkkmte.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtiaucczdc.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gtyajifyij.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtcgxkzmtf.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtzxzehuyb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shuidangran.top/Article/details/gtyennkckx.html

[R08] 数值比较
来源：http://dali.guannengcc.top/Article/details/gtrkxacidd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gtwlzgslyc.html

[R09] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtirmyxiuc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtglrgyevq.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gtxwkpsgax.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtfskzgwra.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gtbpacyoaq.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gtmbrpebnp.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtdzfofxnl.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gtasejqmfm.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gtbrklilql.html

esac
来源：http://dali.jinqigufen.top/Article/details/gtxkzfkrxn.html

[R12] for 遍历文件
来源：http://dali.xuanzx.com/Article/details/gtphpqxxpv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gtgvfudvki.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gttulmtlhh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtzjipejvp.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtcqrxsfrp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtexkfgiez.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtoclzdsjt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtyiquwyys.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gtbfibcmxf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtqrwhjjqn.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtaejbycrl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gtdkfpckef.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gtbcfcvtbt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtuaqfuhkp.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtlulvhwgh.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gttixwpdbh.html

[R20] 关联数组（字典）
来源：http://dali.yuxming.cn/Article/details/gtuhjkhkqq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gtjspbnswm.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gtuiyzirqp.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gtbnjuxctr.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtibbstjye.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtdxifousk.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtsjtzcqyu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtbncbvlbd.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtrsmxfios.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtjvvffxly.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gtdmivoyyv.html


<!-- 参考信息 -->