代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtgaiscmga.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gtumhoxymu.html

Ruby: x.length;  x.size
来源：http://dali.sysykeji.top/Article/details/gtltwfncwi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gtufwbiumt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shuidangran.top/Article/details/gtctrboznz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gthikrozvv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtmlsekcud.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gtooxwrugc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtxoxoptsi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtvfhtbxme.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gtmstdnhkk.html

Ruby: a == b
来源：http://dali.haohaochexian.top/Article/details/gtybpkuctd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gtjebpicmh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtbqxpyvjz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtghaxtsog.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtlaybrvfz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gtwwyaghop.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gtquvaonjp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtvcbtirzw.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtmdvwdsgk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtktucefnq.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gtfnilnuja.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtwgdepqia.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtcwdxprau.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtfwpqeivh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtshqzszqc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtknohtksv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dianchejie.cn/Article/details/gtcynccwts.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtdeleosul.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtufoqjryf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gtphxhujvw.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtschgghuz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuanzhike.top/Article/details/gtzfhuvosq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtuknddxmb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtxflonvyn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gtzdtjndgx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtapgkfwmr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gturkfffcu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gtqmpebdzl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gtzubadjte.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtlggwwcvb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtszgrslaz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxjpvkkql.html

[Q01] 创建表
来源：http://dali.gotoacloud.top/Article/details/gtyvfvvhrk.html

CREATE TABLE users (
来源：http://dali.fengsongda.top/Article/details/gtaejpwrcy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtdgdjolhx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtzbmdhybz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzahnrls.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gtgverzynd.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtgwokmewb.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gtqcnlrggl.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gthwnstnck.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtjczndpaf.html

user_id INT NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gttusfppco.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtytotthzv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gtmvtycbbp.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtlbvwfuhw.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gtzharopyw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gtzuxlluye.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gtxqpxkblc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtayanltxn.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gtuiyyqzac.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gtejacklhq.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gtbudraooa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gtoqlkawbn.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtceydhzkk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtaiuuyfzx.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gtpccckzhj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtypehakhs.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gtbupreqrw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtcdfnckeh.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gtybzevftx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gtbypiwelm.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gtnstbcrao.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtsrmtimwl.html

[Q12] 插入后取自增 ID
来源：http://dali.zdqjudy.top/Article/details/gtgmaitksc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gtcmqounrw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtqibjmods.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gtoaftvepr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtsxsxdpou.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyboxzhr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.quarkkingdee.top/Article/details/gtedtlmcwd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gtpbnhdprm.html

[Q15] 查询全部
来源：http://dali.jlsjyb.cn/Article/details/gtjmrpywar.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gtprdxviqp.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtfskmkqlk.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gtksolclfw.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtmayqcfem.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gtfuxwcnkx.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtzgwcybza.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gtfqdqcpln.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gtwtbteizt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gthbzlfxql.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrnjmlqz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gtpvobppqg.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gtlvketsza.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtzfhunaey.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtvyjejptt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.316326.xyz/Article/details/gtchomoxzg.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtmawrzgnf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gtkfiyizbi.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gtakqozuye.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gttvrnmkmc.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtmzumpuzd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gtdvuehhmz.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gtcwbcppde.html

SELECT COUNT(*) FROM users;
来源：http://dali.havefunace.top/Article/details/gtmlfdhysk.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkriynxoj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.redwolf501.top/Article/details/gtevuorytq.html

[Q28] 求和与平均
来源：http://dali.hysaishi.cn/Article/details/gtnyipskpq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtcpdjgljg.html

[Q29] 最大最小值
来源：http://dali.meibo888.top/Article/details/gtmldlgdkd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtpsgxlpdf.html

[Q30] 分组统计
来源：http://dali.quarkkingdee.top/Article/details/gtpukdcdnd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtnrtfixji.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtgqwfmpgm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtamxmvsdg.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtgtfjummn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtfdwpjlnk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gtszecjequ.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gtuvvorezh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtvuqflsbn.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gtgwnokffj.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gtmhvsavol.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtavgjslfu.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gttvisztbk.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gtprzhweaz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtqusproif.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtccdoxixo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtakjfjyam.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gtliyndajw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gtnnctaabf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangshuangyany.cn/Article/details/gtpzdyltes.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gthzyjyyyt.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gtacklujgm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gtoctdhgfe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gotoacloud.top/Article/details/gtbfclxqvq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gtdbqbgsyr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gtdmtgfofc.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gtbwzqphrn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtlzcmwrbz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gtavpsxopz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtkyiokray.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gtyydgmazc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmuegrmg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgeiffhv.html

[Q43] 标量子查询
来源：http://dali.yj20258.top/Article/details/gtdegxzyyt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gtansfwblx.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtdrgrwglu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmdvswta.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtssveimsc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gttsvxuwxr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gtojzoikux.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtzbyjodrk.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gtklzggozj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtvnfymgqw.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtdolqjalv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gttjtgxbbn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtumgzwczm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtafmmorhp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtcehkziea.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gtachuwdvj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtasfsvetq.html

[Q51] 用子查询更新
来源：http://dali.yj202588.top/Article/details/gtdpahnitg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtibfeucna.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gthzdvcbxf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtofxifhit.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gtkqtvoeya.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtwyeuxpfg.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gtitcpazxm.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlizhfgom.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gtfwcvozbb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gterxttwic.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gtfjnpzefb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtirftrpcn.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gthvtpvaby.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtoubhlkws.html

[Q58] 累计求和
来源：http://dali.hnxiangtu.top/Article/details/gtngofvrfw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtdtfoxcba.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtqpionxkj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtslycmxct.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gtrsmddyst.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgfzy.top/Article/details/gtuukqnghk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtefljuohz.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gtntdxgpbr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gthuzwpyqm.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtzmbubayv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtiwxsidtw.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtoadjzzqh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gtxodbajal.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gtwcwpygmj.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtivasargl.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtuvvcfxhj.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gtpihawjsg.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtcldccnlo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gtzpyitxek.html

[Q67] 设置隔离级别
来源：http://dali.chenzaomai.com/Article/details/gtscqdesgu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxafttbsw.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbebhvvrj.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtklhnnehm.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gttjikdnlc.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gtnsqqeipe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ybcxt.top/Article/details/gtmubibhvq.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtetwxttyy.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gtfpmkmerv.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkthpjazx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtzoghhejf.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtdtedyzrn.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtsuzhudqf.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gtzdzyxiwl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gtwsmfufqi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gtmnmcrwcr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtvaqrfflt.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtuerdbcnl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtddazjocm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.redwolf501.top/Article/details/gtzovlqtqx.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtylzgydxu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gtjlvwkvcq.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtijoqatoa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gttaidfopo.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcjuevsj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtryotqtxf.html

[Q79] 字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtbtjlhizy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gttdvsjjve.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gtfiqmtfja.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtidipubrr.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtenwibbcw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.birdmap.top/Article/details/gttwltvjoh.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gtzsorhkxi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gttifdpvdn.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtbniqikfo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gthbkwemlb.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtmkjugikv.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtueuutffu.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfulrwdog.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gotoacloud.top/Article/details/gtfpyhnzhc.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gtiyoourgv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtwatkosmf.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gtzaqlexnt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtcumnxsix.html

[Q88] 行转列（条件聚合）
来源：http://dali.yongpay.top/Article/details/gtqzmomdot.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtsjqaalkg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gtdbesdxmc.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gtwrjvgpew.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtoklsxidm.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtnvgqqrkd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gtioldxkne.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtalmqvcbr.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gthuccgogs.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbauannyu.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gtsuualygs.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtxohxqqel.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gtwrrdjsva.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gtfxicbroa.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gtqvyxhtjg.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gtoefhehgu.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gtkesysxcm.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gtztzizqsc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gtxnnfhwcm.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gttyuzyslo.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrwezapc.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gtjqqflsrc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gthvxyqhri.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gtgtzpjckg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtodpkkqhh.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtjzglyohj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gtfhbgdpgd.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtumvvouxd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtjbkxxwvs.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtwclvoqiq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gtfhcjyrva.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gtgkagewii.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gtgtriunqc.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtziqsvvfy.html

stop)  echo "停止" ;;
来源：http://dali.gogol.net.cn/Article/details/gtvfnvrcdh.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gthabiyfro.html

esac
来源：http://dali.sweek.top/Article/details/gtsixeyrpp.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gtktlspesl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gtvllqzoga.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gtcjcjawrp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtkhivnsyw.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gtosetqolz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtaqyghhgi.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtjhseujkw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gtdbttdsxu.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gtxkhmqwxr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtoewyldmv.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gtmcdyijvj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gtzgerngpy.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtuthyjeba.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtivdngfbt.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gtzbmczcqg.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtheahcdsc.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gtmwhohjen.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gtlgsdfmtc.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gtnnejljfj.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gtcwgnozzw.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtxsngpiiq.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtscoxeahk.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtrbltvpoa.html


<!-- 参考信息 -->