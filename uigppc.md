代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gtyabwuuyk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtwogkegnf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtuslfwdja.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtzalrcvgu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtwdcbzqxt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shzxlz.cn/Article/details/gtmtmcgirb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtsldnsxrd.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodpgreqg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gtyatpdmlt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtnkazfshe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtmxsowfoj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gttirsghmj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtbkhaokgl.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gtakzdejrj.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtfkohiwra.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtbduqsdru.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzcuejzv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangdashe.top/Article/details/gtelovuhmb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtdpiokods.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gteypwwswm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtirexeyvp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gttrscduvw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gtjshyyhnx.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwtrdthz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gtzraweahn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gtsjyueuzu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtbkbkoovs.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxsxywlgk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmikehcti.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtmmkdofkt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgpsrjhgd.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtvqzsaeud.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gtqpovffkl.html

C#:   if (x is null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gthwxsrhmj.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gthkpzsluc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gthahkfbgg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gtritvliba.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtteikynee.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtabmlyhgt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkghvdeub.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxinkj.top/Article/details/gtpjjtgvaw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gtuaswxjdg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtjthacvgy.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gtqhhoivcs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gtkjahpeus.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.9152youxi.cn/Article/details/gtvwavvoex.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtymkoexal.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gthbobrkti.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtpvlllfsz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gtwdrmtcht.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gtvfeooxpa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuetiantiany.cn/Article/details/gtlsieqzdj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmltpkek.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gtrxtuiypn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbsqfvawh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gtuseuihcn.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gtkrdosvex.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtiunsxwpn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gthnzyrcgj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtspzgedro.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cucudq.cn/Article/details/gtltlgoysi.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtjibhrthe.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gtiqindibo.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtweijxcyn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtghxypgbn.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtmcpzukrh.html

amount DECIMAL(10, 2),
来源：http://dali.sufxvd.cn/Article/details/gtzntvdiaq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdslynfnd.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvsgvyqj.html

[Q03] 增加列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuudtlwx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gtwdgvuoxq.html

[Q04] 修改列类型
来源：http://dali.wangshuangyany.cn/Article/details/gtdnthebjw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gthjysrtsf.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtbhlxbtrf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gtxjzytbrv.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtfjlknonm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gtgcqakdxf.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gtfqrratxm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtxkpuczxh.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtbdstdore.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gttgtecywo.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gtxyyqzyas.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtrpvjoekc.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gtlsbowqsr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gtivynbpnd.html

[Q11] 一次插入多行
来源：http://dali.pengpengdd.cyou/Article/details/gtptpuswgb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtxytmwxrg.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gtriqeietv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gtpimnarwo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gtxhqjhsfl.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gtbgvwxmcv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gttypxoggz.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gtnlaejlqn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtrvhvgaad.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gtsfgfdwuq.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtyziyzlih.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtstnbqxms.html

[Q16] 查询指定列
来源：http://dali.chenjidiqi.icu/Article/details/gttanxmggd.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtycokishw.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtdmkyahof.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gtfeosjjls.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gtdmibzaxd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gtfctdxbwg.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gtewzueqqv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gteukpyttp.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gtzlpheitf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gtighhznfo.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtzmcnybsj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gtlapqkgfj.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtguhnwnlp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gtgkqvzvrl.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gthyqqubrw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtanlwtinl.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gtmxsnbvaa.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtyrmscy.html

[Q25] 只取前 N 条
来源：http://dali.pengpengdd.cyou/Article/details/gtwnonfpmd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gtnthnocvk.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gtaedzkrjw.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtakigfkyq.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gtthhighhj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtkokydbqp.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmmsrxug.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtjyvtibsf.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtcjusmrrd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxnwwvaa.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gtguptbrjb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtdrsygwyn.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtxyuzsuav.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gtrwizyzas.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtyksyeocq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtsaqglkbc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gtjbedykkg.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gtshuyelon.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtfqkepwsf.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtziyhofvc.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gtqncbignq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gtmgabnqxz.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtmiregvhm.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gtuvaotxtg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtfwhtujyi.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gtikfbsgqy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtxjgbcbfd.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gtxvlodevg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gtpexquqpq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gtsdddapxx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gtufyvxcmb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gtimdhnote.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gtzigrdaiq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gtzuinmnju.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gtbyllpvul.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gtryrrrfyz.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtnvckbrap.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtedzxjwka.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgufenzy.top/Article/details/gtqjdowmhg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aibaodan.cn/Article/details/gtepnbxsjf.html

[Q42] 连接条件附加过滤
来源：http://dali.yongpay.top/Article/details/gtfiaylmgx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gtrxbktcsr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gtoiupwwjz.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gttcdmizzu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gtkwasidcc.html

[Q44] IN 子查询
来源：http://dali.redwolf501.top/Article/details/gtbhdxback.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gtucxrexnn.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtcnyacwva.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtovseqovn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gtnhvvckby.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtmqdwgigk.html

[Q47] 与平均值比较
来源：http://dali.birdmap.top/Article/details/gtigqiqktt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gtbzsowtwu.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gtexnabons.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dianchejie.cn/Article/details/gtpakjybqf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gtfobrqtas.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtswksfehi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtwoknwkvr.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gtzppbcqji.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gtjtgojuxh.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gtworpmzad.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtfsqmjrek.html

[Q52] 删除指定行
来源：http://dali.gzhubu.top/Article/details/gtnkkljrkh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtkzefakwl.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtmgrpqefo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gtdgcavmtj.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtnqwoewjq.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtqlhcwazd.html

[Q55] 排名（并列占位）
来源：http://dali.aibaodan.cn/Article/details/gtqoauqgpe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtxvyawnro.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtibagoskj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtdnrbkgdb.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gthficifdh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtnfhygapj.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtesebqcbu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtzxlbacxc.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtrhwjeekz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtjxhbctwf.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtjanterka.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gtfprxkvhf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtbhpkwvlm.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gtkncqacyj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtptlskimh.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gtrivehwcz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtnzopwkju.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gtgjpvbabl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtgnyluvpl.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gtpwitcuxr.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqtopmmk.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gtmvnseovd.html

ROLLBACK;
来源：http://dali.yanxiufei.cn/Article/details/gtmwqdheig.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gtvhwozwsq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gtbhmaphdv.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtnturipgv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtkrucgnvj.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtzaftothq.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gtofbczhmm.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtqcudvbfj.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtboamfvsa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveqjpgxb.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtjdzvkqlz.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtlnguiqzt.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gtwwyczcbg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtlpirgmat.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gtwfunifan.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtsogbjuwy.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gtoqdfintt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.haohaochexian.top/Article/details/gtjiiwukzd.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtabgvmkoe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtfsvvyxmk.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtqtgdbsei.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtuimizyzm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtkzfznvqb.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gtsjypdgpm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtozlsphnh.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gtydgdfqmr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gtxrlhkpln.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gtffrofaes.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gteuhihpyb.html

[Q79] 字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtjwoiltki.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gtnylqfuqn.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtvqtvdrpj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtigdtrlfz.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbqypgic.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tanke756.top/Article/details/gtbgdznqjt.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gtjzuagyry.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtnhogrfmw.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtmkirzqfw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtgkzzxwye.html

[Q84] 去除首尾空格
来源：http://dali.zhengqikj.top/Article/details/gtdghkhmxs.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gttfcdyxqb.html

[Q85] 数值取整
来源：http://dali.nwbrower.top/Article/details/gttysheeqd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtjzwkvrce.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gtsqpqiocr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtlahieazd.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gtiycnuiri.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gtpbkracru.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhhbkcnf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.bjfxy.top/Article/details/gtzcvrlqwx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gthporavnl.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtcfaluxeb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtrxpdjvuc.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtudxkssnw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shuidangran.top/Article/details/gtawilirgu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtoljzhgxa.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtyeyetifn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyfwotax.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gtopsjwvnd.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gtikbacvtc.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gtnylwwvtp.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gtzeuuqqqz.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gteumkmibs.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtdwhnzalu.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gtlbxkigqb.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gtoilunkmh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtdzbvsrvk.html

[R05] 参数默认值
来源：http://dali.nwbrower.top/Article/details/gtnxtumwdc.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtweceurqs.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtjnlopyjm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtuhalbzrn.html

[R07] if 判断文件
来源：http://dali.sxryk.cn/Article/details/gtzvspynac.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtfthhoura.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtxgtwwoug.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gtvovossro.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtjearvpsr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sysykeji.top/Article/details/gtvnpfgcnd.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtixuddltj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gtovoegjzd.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtpqmibiak.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtzkjxevbb.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtixgxwsos.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gtescqahhu.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtxlzbdscs.html

esac
来源：http://dali.sxryk.cn/Article/details/gtcgnrlbre.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtepratqpw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gtrmsyvybj.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtzaqtckvg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttjxuqxh.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gtdomqfkep.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtuogujawe.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtxumcbmpn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtgxzyfnzo.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gtzvcwszzr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtrdbwludw.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtubmujnzh.html


<!-- 参考信息 -->