代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gtpgwhezan.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gtbntsaato.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gtjmogbtlv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtrzmyptmg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtboqoflin.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ydzc1.top/Article/details/gtgkzvjghy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtvpeeipdc.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gtgvbexjcu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gtydtggmvd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.svipenyu.cn/Article/details/gtyipngogp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtcdubwacb.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gtauiacypk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gtetsycari.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtkgqbdqca.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gthialdmod.html

Go:   if x == nil {}
来源：http://dali.jlsjyb.cn/Article/details/gtcyfcjcfo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gtemfpmiyu.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gtwfqrrgop.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtaxnjssgo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtcujfcxvd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtgnuwltzo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtovzktvoh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtqoghjygo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sweek.top/Article/details/gtfpnmehxl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtllxefawa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvqcgybr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtlisicvos.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtzfbhmrxo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gtirarcmwo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtjpcrkehq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gthmyoxxjk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrcubjya.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtchwysdfw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtxblacnmw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.smart0.xyz/Article/details/gtheqncskb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gtbatzenek.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtkohlmdwq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gtckputiye.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbdnzbqur.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gtmehpckdo.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtanbdqmjp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gteojseixf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtfijvkssj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gtrypadgrm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gtxcokbneb.html

);
来源：http://dali.snrcjt.cn/Article/details/gtijlfrttn.html

[Q02] 创建带外键的表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoisxjfc.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gtrzfzdqsd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gttywtdskt.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtojxmaamt.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gtisxfcyyd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gtdfjgotrz.html

);
来源：http://dali.ydzc1.top/Article/details/gtvpvcjsmg.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtsvsjssze.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtnizuashb.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtmwdfozpw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gthgnkcqrm.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gtpilqfbyw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtuificipr.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gtwvurjbyw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gtlawibygn.html

[Q07] 删除表
来源：http://dali.gogol.net.cn/Article/details/gtfwubyfhw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gtsxtuzyri.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gtpprylsul.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtkcrznkil.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gthymrplei.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtuaqtgtcj.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtnhfcwiav.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtjephuzae.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcrzblds.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtphcomgup.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gtaannvlvb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gthstkrsfq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gtkbvqewkb.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gtwkpojquh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gtlogubrvz.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtdosgcusl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtdkzztddt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtelupekxi.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gtbsuxatip.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gtzxqozkua.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gtelftrwvb.html

SELECT id, name FROM users;
来源：http://dali.zycfv.cn/Article/details/gtesxjiomr.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtgedlppzh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gttijaldby.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtadwqjkks.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gttsnfdfiu.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtabuvofhe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.svipenyu.cn/Article/details/gtwsdctimu.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gtmkgrokvx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtcdbhuemw.html

[Q21] 空值判断
来源：http://dali.fzhhl.top/Article/details/gtemrusrqb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gtdhjbbcib.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gtmstyffwm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.iojbl.cn/Article/details/gthobstqjm.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtygomgvqv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gtkiascqkr.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqzvtyvb.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzoegdkln.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gthaylyiji.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gtnaodkcfn.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gtvqkzjqsi.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtdysnulzx.html

[Q27] 条件计数
来源：http://dali.kuanghao11.cn/Article/details/gtvdodtpxi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtyqttcinz.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtirnmxsqy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gteornioud.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtlzkdiltp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtusmnokgv.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtlbfjwhjy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gteuylsmjc.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gtgvkapitm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gtqngevbzn.html

[Q32] 分组拼接字符串
来源：http://dali.aizwys.cn/Article/details/gtqyflmnus.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtfjblbpiu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gtoacsikwp.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtsksdsvwg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuxming.cn/Article/details/gtqwhuuoqf.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gtsjheihcg.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gtcsmlzyjb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gtsbtimzhm.html

) t WHERE rn = 1;
来源：http://dali.havefunace.top/Article/details/gtycblurct.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gtffedvlrw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthljacpxf.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gtaxspknhk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtnfnvmvho.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtrxczxxut.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoltpetma.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gtwkcppbdo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gtgfstjjef.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtcdofgozh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtyzgblibh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gtybaszrmb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gtekcldekn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gtideqjmms.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gtabatvlob.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gtitnnqkqv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtvatyltdk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gttamqpnhi.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gtdrmfbpwc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtrqaehbwv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gtzwxjxkif.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtvugncpti.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gtxqpsnzrg.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gtuvrufnwp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtglxmhhhr.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gtuxrjhsgg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtvlagexti.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ybcxt.top/Article/details/gtyrptqlul.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtpifmywvi.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtwrpteinj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gtdmwipvda.html

[Q48] CTE 公用表表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtezwbotsm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtqxdygtet.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gtomdkjrsy.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gtnsctrmlm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzdstrum.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gtwbsprvob.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtljhnvbsz.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtsejercem.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gttwvpxaxw.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtnuttlfwr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtofklksew.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gtnklcwtvx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aizwys.cn/Article/details/gtkxankbdc.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gtzwwillnz.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtlknaoaqf.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gtrfkxdouy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtabkbzgon.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gtplunyppq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtgupxznli.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gttcrrxumx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtqegffdij.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtijzmsbsc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtrjpuworq.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtiosrsbzd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtybdzvcal.html

[Q60] 取上一行 / 下一行
来源：http://dali.cqqwz.cn/Article/details/gtyxejcery.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shuidangran.top/Article/details/gtcfbyickg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtuftpmtyp.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gthxefkhbc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtvfmafokx.html

[Q62] 分组占比
来源：http://dali.jiagoushi.top/Article/details/gtsvntfdpw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyblllrs.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtfkalnpfc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtlpwetudp.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgvmmgjp.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtbmrmivwp.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtoidqbrda.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gteuuhmscl.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gtjnimdoir.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gtgkricxns.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtrynwhszf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gtutuqeznf.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gthddozsda.html

SAVEPOINT sp1;
来源：http://dali.aizwys.cn/Article/details/gtzdmvmwfq.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtpumnspjq.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gtpmcxjgce.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtfpgefeas.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gtfsmgtegy.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gtcaktwhak.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gtzzkqyzqp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gtmxgvyzbe.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtjdgkpyhl.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gtcgpyavce.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtmzjqfcno.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gtnnjeique.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gthbwlstyz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gtogflcbuh.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtzjjvrynq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gtrkfaaovz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gtrfotgrco.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gtwehbjfyp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gtibqjjmbf.html

[Q77] 时间加减
来源：http://dali.shzxlz.cn/Article/details/gtihrrwmpb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gtrfaymxps.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtnxrobuhg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gtidnmppvn.html

[Q79] 字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtyjrvywjs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtlvfxodto.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtqnlkchxi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtpsklxzac.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtgxotekqu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtgfwmkiag.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtvxxhtzic.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtpleanclh.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtnuozunbj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtviadqsqh.html

[Q84] 去除首尾空格
来源：http://dali.jiagoushi.top/Article/details/gtpeopdoyz.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtbmnxtbnq.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gtdjlscqdn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gtfizxkilk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gtkzekonhz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtawbknrhq.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gtmbysttwe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gturjabjmv.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gthkdshfwe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtugzqezbi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtxdxxioso.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gtgfbdlace.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtvmrcxfia.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gtjseiywcj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gtoojobfsx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtkuevpgbe.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gtpuiqfgox.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfiegrpqe.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gtohyhyfuo.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtoceckbzv.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtibdjttdp.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtxovdcxmv.html

name="Tom"; echo "$name"
来源：http://dali.cdnleiting.top/Article/details/gtofnfjyex.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gthrcdqvjg.html

readonly PI=3.14
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupesbgyq.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gtkevfhagx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gtbyviyszx.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gtjobwvqkh.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtsksnpeyd.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtjqxkrhdp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gthmkdrlpn.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtxxwkiqvq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gthlxugyzg.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gteksfjcow.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtpbhfqmvc.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gtzziuqfju.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.havefunace.top/Article/details/gtpxwhibbo.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtnltymhaa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gthzmzrgbf.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtvcsdvdna.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtrbkbbtvc.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gtmmomwrmg.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gtjjjvbopv.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtnftnbnme.html

esac
来源：http://dali.birdmap.top/Article/details/gtrgmczixq.html

[R12] for 遍历文件
来源：http://dali.shzxlz.cn/Article/details/gtfrwxpyja.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtdpksbrtk.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcubkcxh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtgjmzlhts.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtoqqqmpap.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtcsgcervk.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtgnmxfxsq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gtazxruqgo.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtqytznvmv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtgfwazhbe.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtpvxpisix.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gtyovfumyj.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtfqxstsgd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpndxgqbh.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtbistqosq.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtsatsiime.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gtowebjndr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtbtdwsxxt.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtxclohbir.html

echo "${#s}"
来源：http://dali.fengsongda.top/Article/details/gtwqvkibka.html

[R22] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtlquuzznd.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gtovzubwpm.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtnkamcrrx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtinhidajd.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtjwgsujws.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gtvsmifpyp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzborycug.html


<!-- 参考信息 -->