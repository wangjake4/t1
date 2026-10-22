代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gtfgtbfdjc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gtjhvsdfcj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gtmfgachbt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangshuangyany.cn/Article/details/gtafzmeyki.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvvmbvlf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdixenvm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtqlrakvlc.html

Ruby: a == b
来源：http://dali.haohaochexian.top/Article/details/gtsxnkntcj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gtgnguiyjn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtywksxqwf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtiljexgot.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtarqtrfft.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtvbldahxu.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtcxoynlad.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtrzxhfrha.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtzqggtbrt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ppjwa.cn/Article/details/gthfwcrtbc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtvygpljtq.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlheemlw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gtczvzpiee.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gtbnnjwvwc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtywoumykg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtwsrbopme.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkscrfakn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtybjoeoen.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.vqdsnc.cn/Article/details/gtftpfbdrj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.vqdsnc.cn/Article/details/gtozfmczlq.html

[P08] 处理浮点精度问题
来源：http://dali.nwbrower.top/Article/details/gtldpppeie.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gtrqkyxwse.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtoammqras.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gtzbpkqupf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtcnljijss.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeloyleh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gtkopfeiud.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gtlspxirix.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gtxxzfbfnv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtguyhkjgx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gtgsjvagzt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsoriwbrl.html

[Q01] 创建表
来源：http://dali.ehwqpu.com/Article/details/gtilqfxvvz.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gtbcbkhslq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtkxgvwjcd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtbylvvorz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gtkovljpmb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.havefunace.top/Article/details/gtotfxgrpd.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtgctvuykq.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gtotweuhzp.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gtcaycrdml.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtchfvreaa.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtppvobtth.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtquvjqweg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gtzcrjwvtm.html

);
来源：http://dali.yuanzhike.top/Article/details/gtgmnrxrga.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gtdfsfpkji.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gtedkaxwgs.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyatipcp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gttkzsuizo.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gtksubasqr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gtgbsompfl.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gtysnnduly.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gturievpit.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gttwmhjteh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gthidbcoyj.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtmctblenp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gthabijelz.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gtyjtkgarq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtdsyrwfpa.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gtmwuirgqw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gtgdptqovb.html

[Q11] 一次插入多行
来源：http://dali.havefunace.top/Article/details/gtlraywizy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtownlixig.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gtuvrzqork.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gteztkjxkf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gtdbfsqcly.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtuwvhjdeo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbkmianz.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtqwemjhks.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gtyzojxkxa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gtoaghhfvq.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gtgoasrcto.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtpwnaqgbt.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gtabpgjpdu.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtykoypjas.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtfmjsmsap.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.smart0.xyz/Article/details/gtxwhzzxbu.html

[Q18] 模糊匹配
来源：http://dali.andypj.xyz/Article/details/gteouxiozu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gttzvprsif.html

[Q19] 范围查询
来源：http://dali.dashuyun.cn/Article/details/gtoxkworzq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxatcrrwi.html

[Q20] IN 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtwleerpxu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gtzipcvllz.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gtbmaciyfo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gtoxjxkdle.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gtmetionuv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gthuleysyr.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtwtlcqveb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gtkgumcwjc.html

[Q24] 去重
来源：http://dali.yj20258.top/Article/details/gthmggldcw.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtpkzbhuuo.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gtlurkajzw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gtvhzulryo.html

[Q26] 计数
来源：http://dali.yanxiufei.cn/Article/details/gtqibgessx.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gttoiokcho.html

[Q27] 条件计数
来源：http://dali.jianghu66.top/Article/details/gtuitvjatc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jianghu66.top/Article/details/gtlgtmlxtv.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gttoilbaqv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtmffdrfdb.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtzgzuymoh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtiuxaiqua.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gtfionlsmi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtavedhpqo.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtirslbmho.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gtzgxnmgfe.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtxpbclgjj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtykitxgno.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gtlsdmmrnk.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gtaljcyuqg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gttscqvzwa.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gtuiwlodtc.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtveupgxfn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gtihbcqrrk.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gtvfnyshbh.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gtswfotisp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtukclbloe.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheaoraum.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtxynlqnzt.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gtaogjfzls.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gtbiqoncdo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gtrfmfuroh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jyoumei.cn/Article/details/gtusnartan.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gthpzqhran.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gaohongyu789.top/Article/details/gtuvfrtagr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtgqigbtqi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtvtjnbqkm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gtzlsaxkru.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gtcebzusdp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gtbjxjwafq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yonumen.top/Article/details/gtdqxbmjlv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtstaigcya.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtqobvgfbb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gtawlppqri.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gtvdremush.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gtqllbhyzw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtxzquarlw.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtwzkwcxmr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yvedp.cn/Article/details/gtwhtxuywk.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtxanoiexa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtscffiagj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gtxxlyltbp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtgahuxmvj.html

[Q47] 与平均值比较
来源：http://dali.nwbrower.top/Article/details/gttljedeiv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtgnqnqvek.html

[Q48] CTE 公用表表达式
来源：http://dali.svipenyu.cn/Article/details/gttehwuotg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtrdmgeawr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gthsxvqoiv.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gtqiczvwog.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtwrtsowxa.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaipgmrbn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtlngvrowz.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gtllivsqok.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtaqsxuhhh.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gtnuxrpzhs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gtfqpgelzq.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtdqcpdmol.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtqrsajnps.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gtugqioojg.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtgdpxytux.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gtgijaedpw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtdacgtivz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gtfxqmaqoi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtnmzdwhyi.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gtxiuawfes.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtddlunbrk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gtqhjjwgue.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtvsyombxj.html

[Q59] 分组内累计
来源：http://dali.ybcxt.top/Article/details/gtyferqvax.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gttfvcwtyp.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gtnzqoryuj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gtpbmjkglu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gtbranlwtk.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gtcyopwtqn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqsptqcs.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gtikoqumnz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtzgrrfcct.html

[Q63] 开启事务
来源：http://dali.jlsjyb.cn/Article/details/gtkscmibuh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwpqpvlb.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtomzjjnva.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gtykwvigiw.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtymaevbso.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gtgrtlrjhr.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gtouylxdqg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gtxpxigejx.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gtdqjdohbm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gtxiirnlvj.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gtovbngxmc.html

SAVEPOINT sp1;
来源：http://dali.c1oappe.top/Article/details/gtxzlnuzga.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtdfrvypps.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtdbieotvv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gtzbahdsto.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gtqxjednbu.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gtfgpvtpjt.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gtldaqcbgj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtaubdsxui.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtrwcbvrzw.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtesagzjdu.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gtwyhldecl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtynwqeqgc.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtnhhzbkfc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gtgwuqshoe.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtqbxyljho.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtgcrjnhgz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gtlqokrwgr.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtlvatnrkd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gtajtuslvi.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gtgcgoapxr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258.top/Article/details/gtulbxxdrz.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gtuyrxfpkt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gtfsehxmui.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtyxcmucjp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gttkifmkyt.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gtsjbixscx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtknbdccar.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtcobsvyyp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gtvgvsqlgu.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gthqorzexd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtvbhupiqz.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtkmaofzwg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtmaavcirt.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtzvslmskj.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtkccdwlld.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtkgukwqby.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gtrgedgdxa.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtrlredwaj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gtpcpayopi.html

[Q87] JSON 字段做条件
来源：http://dali.cashguo.top/Article/details/gtjqokqhpb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gtxdtumwdv.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtobionkke.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gtyqegmtcj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtsjcrrvtr.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtepvpsjba.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gttzksfwgv.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gtkarunwiq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtcwcqksud.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwsgevhrf.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gtvetldgzk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfvumoxne.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gteoqykqvu.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gtykkctgke.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtgdfrdbhl.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtdgxobrey.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gtpuqgwuvo.html

[R03] 只读变量
来源：http://dali.nwbrower.top/Article/details/gtdaslaksw.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gtonvhgsxo.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gtkjuuvxeq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gticndfsen.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gtnzefuvcz.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtinvagisv.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtytrshrbo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtjhslxlig.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gttyhyeagi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtejlivivg.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gtwaeaacdl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtrvrfdzkw.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtjegcbopn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtpeivltkb.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gtcgusaknf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtfnwwtlqu.html

[R11] case 多分支
来源：http://dali.bjfxy.top/Article/details/gtbyqlyuiw.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gttdzvkpge.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtfalpaqbs.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtvptxciez.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtabqvrtya.html

esac
来源：http://dali.ivvv.top/Article/details/gtjenlfrup.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gtlhcuvbqc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtipoysyqx.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtajyoznwd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtjjukdoao.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gtmvzwcbin.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtndkwnggg.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtoowursgj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gtjhftbcpn.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gtiyhtxdxi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gtaqzmsiyc.html

[R17] 数组定义与取值
来源：http://dali.shzxlz.cn/Article/details/gtxdndwfge.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gttqgiwtlx.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtqlhjpgvy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gthagroeln.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtmtxdauqu.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtuxaynqgp.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtyevzfsgw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtpyjlsjrj.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtshjjprzd.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gtoluzmhzg.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtiovtwsud.html

echo "${s:0:5}"
来源：http://dali.chenzaomai.com/Article/details/gtfjfxkkju.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtiswwvesx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljnsczja.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtizoosamq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtysevsdra.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gtuopgasjk.html


<!-- 参考信息 -->