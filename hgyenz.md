代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzinrtpu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gttodgltou.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtzvoprnjb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtrjnllszr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtdwikldso.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gtcyepxqok.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gtgbgbyyid.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtzuvgjgqj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shzxlz.cn/Article/details/gttyyrnwjd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gtonjktgty.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtmgmyakdi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dianchejie.cn/Article/details/gtwvypdxto.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtcoeoobfk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gtehxnikxj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtdkynskcj.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gtdlhcwugf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gtvslqdilv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hysaishi.cn/Article/details/gtjjtcchtf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gtrrbrkfng.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtiagmsowv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gtgbtygbhv.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrdudntc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtmfdvwqiz.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gtcysguyqd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gtxazdajqz.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gtxbipbyzc.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtiisxoclz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gtmuatytmt.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgufenzy.top/Article/details/gtgpolxeqw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtimbctgpb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtalgufhrr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gtektajgnn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxinkj.top/Article/details/gtrsqryqxd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gtrsxxkuwj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtwhzrhlwt.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gtuhfzffjt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwleqihwu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gthvgdkkfk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gteiuwaolb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtjbypfhwx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtljysmgaq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gtlhsauclg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gtayaakloz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gtdsvfjjqe.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjqlnxgsj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtyszzmujd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtczyxgzvg.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmreviidi.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtqkksotmz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtljyztalm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgazjpre.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gtigfurwda.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtevlpwgkv.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtzouqiynx.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gtvogahyku.html

CREATE TABLE orders (
来源：http://dali.jiagoushi.top/Article/details/gtveslcdsz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtygxxptqg.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtvpmanotn.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gtmkjmszlc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.snrcjt.cn/Article/details/gtjymprwwq.html

);
来源：http://dali.chenlongwang.top/Article/details/gtcjtgiocw.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gtmgflsnjw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gtrwwypzuh.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtjlqxfvkk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gtuogfizag.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gtmyjejyil.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotqzgvcm.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gtcqpuelui.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gtuuhylulb.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwpflwlx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gthowepbal.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gtlvduffwn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtrnhibjyx.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtpquufnqx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtundqkugt.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gtymnfigtt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtklmdcomh.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gtalrcxkik.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtjsqlvitn.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gtbaupcbxn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gticlukpot.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtssmtjwba.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtsvrhodva.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtpavdyxks.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gtkivukhyh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtfnrcgbmr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtetiutllu.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtczeqavap.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gtcbaajrkp.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtfyrunzaf.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gthcucmhkp.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtbjpxjijr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gtzzxygahq.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtmmpmmqhj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtbowkmvnv.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gtdxwmsuji.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gtfavkdwbw.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtjapkvbdz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aizwys.cn/Article/details/gtfcstkxzg.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtoqkuotjc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtgyokotoh.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtzqrcermi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gtskwylbqc.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gttmienhfv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtnrkqotvv.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gttaqcaayy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtnpxbktcy.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gtjtwjhtzc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tanke756.top/Article/details/gtmdtftmnp.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtufzoweoa.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtstabwhqb.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gtvkmqgypo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtwhavzgta.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gteaaxsoeo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtuojpsfwc.html

[Q29] 最大最小值
来源：http://dali.ehwqpu.com/Article/details/gtjvygnzyp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtsduldgqr.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtyzjkqwxb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtvsaomrkq.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gtqrsnohgw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtivuwznsp.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gttgggrtse.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtdqpqzojx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtkzyanoyi.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gtexozcrxa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gtrnijjqgo.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gtnduoivee.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpppmkwl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gtukbmfvie.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gtuzeqrjmv.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gtaesowycw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtxeulibwd.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtemdondka.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtqtmqvufp.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gttnaxpxva.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gttlszvbsv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gttaizlmox.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtykfybsvv.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gteyvkfozl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtrjbdpbnk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yonumen.top/Article/details/gtlaizssnv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gtnjemhvxb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gtdcmzogze.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gtgaizchnc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gtbwqtovzn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtdunvhkze.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtetkouslx.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtazyojski.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtejvbhncn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gtezewbude.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gtxdcbgmul.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.feifeiyinyue.top/Article/details/gtgicchfep.html

[Q44] IN 子查询
来源：http://dali.hammf.cn/Article/details/gtqiaevxvc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtztveawag.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtjhjuxgku.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtaymapydl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gtlgfvheeg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtnvkdcokb.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtawhzflgm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.haohaochexian.top/Article/details/gtrshjzyrv.html

[Q48] CTE 公用表表达式
来源：http://dali.ppjwa.cn/Article/details/gtsmzladln.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtiwuslohh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtdvicyyht.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtnnjslmqq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtdybtcnck.html

[Q50] 批量更新
来源：http://dali.tian-w.cn/Article/details/gtqqoomhxp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjdusjuv.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gtzxghugps.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gtsazimqfv.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gtomlvsutc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtfljgblxl.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gtbafrfhqb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gtiqeyzbfu.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtdftojagf.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gtwsopfbxl.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gtoygqmyuz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtsydbodnr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtrouwtymz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtrfxclpje.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtpgrywyix.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtewlsgmzf.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtohynjgmh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gtupguszpn.html

[Q59] 分组内累计
来源：http://dali.ehwqpu.com/Article/details/gtvjkcvbny.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtpfiunctf.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gtckpiwmtp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gthojznplf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gtviknajpe.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gtcnhxdjhb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtqmiaqnqa.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gthrdvdwhx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtqvgnjjul.html

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gtdxbyrlpb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtwaaequqj.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtknqrlabw.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gtoquyzdnb.html

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gtcumhjdtw.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gtrzyczuoz.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gtksdcanot.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtsraarstw.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gtdvezipbk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hysaishi.cn/Article/details/gtxvnoknpk.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gtlodnnjih.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gtmupeofia.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtzugfvvdf.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksjdsxvt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gtjbysqvmg.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gtiwfqxoth.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gtwapurbta.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gthubxvtxd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gtdacqsxvf.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtpjxvbubf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtrgzokrnt.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gtuwvvlqtc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gtrxtgywdt.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gtikciepnf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gtgirsomno.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtijswspbe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtobnnygql.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoiichtwr.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gtyzrfshck.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gtoquylehx.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gtbfgqfzgh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gtpreodlct.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtsmtmjhfj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gtvggrlxke.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuylwnsz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gtcmvcfmls.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gthifzrith.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtmcbbxegc.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtlcreldcs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gtjilpsgbn.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtddmwoecb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtbdlbtxqp.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtqylczall.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtxgderhrk.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtcckvzuuf.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqrvlivl.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gtlwvdciug.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gzhubu.top/Article/details/gtwjarozbo.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gtnzrasuek.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gtsfyrdbvt.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtoagnzkqm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtqzcqkpvj.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gtgzdfygzb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zycfv.cn/Article/details/gtdjbglods.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gtnceektls.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gtnfbgvrjk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gtkntixijt.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gtmjgxdnhg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtlycdsqmm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtiuzyxepb.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gtimgopxea.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzptiwbsh.html

[R01] shebang 与严格模式
来源：http://dali.ydzc1.top/Article/details/gtztcdworc.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gtgwxtdlgi.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gtyioieedv.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtjutxwdgm.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtrznmbkub.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtucqpthwf.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gtjowgzxzf.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gtsnvqluou.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.redwolf501.top/Article/details/gthnqxbmjm.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmpdzbpe.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtfsvpovce.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtyirngtjd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvisvphto.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gtrobehexr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gtwkgnhmxs.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtwhguiimj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hammf.cn/Article/details/gtsrakobzp.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtozxjdnrv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gtgvvfmfoz.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtjdesmriv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtazzyjifd.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gtylzmqqvj.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtfukeofud.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezcmktqa.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzltycqv.html

*)     echo "未知命令" ;;
来源：http://dali.ybcxt.top/Article/details/gtqwpskqcy.html

esac
来源：http://dali.jiagoushi.top/Article/details/gthsweesmp.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtmbfoaamo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gtbxylyyvq.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gtopgpeiau.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtivssnbcj.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gtixfpzdky.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtqazimcbm.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtgzpciguv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gtadpdsdqk.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gtizaoguxb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtsmguxrsf.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtanrmvgki.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtuwxppbtu.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gtfwdlonnz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuontcce.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gthqmugvdc.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gtgltuqvfq.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gttsekctvp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gtahqrypyj.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtshcvasdu.html


<!-- 参考信息 -->