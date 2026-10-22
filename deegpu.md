代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gtybngkapl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gtjhxwfwmt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gthgcjdyey.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtiiwrpkkd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtyiyubrnz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gtgahrhfmm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gttkhrjhxa.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnthjpnwl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gtmtudwsgr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtsvpbemeg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gttkbulxez.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gtjghapefp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hongshengwenyu.top/Article/details/gtvttkuygc.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gtnsfeptdi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtalnizdpz.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gtaqpzxqxv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gtshqutgzq.html

C#:   if (x is null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmlwowjpy.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykxyrpag.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gtsdwxhdmg.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtekpgtunr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdssqzutt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtwrqhloro.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gtqpaontxs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gttqpjgjtw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xziqi.cn/Article/details/gtmyfuqdal.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtmjrmxdya.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gtncmuqkms.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gtqeuohofl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gthcbnrpzu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gttmbclsxz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtwawnasmy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dianchejie.cn/Article/details/gtipvplblq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gtnihnwmrj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrqjlsgt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gtmvhdjnfs.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtsldudksb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidnfzmtt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtccuvbznf.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gtjprpinri.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gtzvktzswp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtyhfgoymj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtipxsjjsm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhefoicr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gtdwmxjxaq.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtdufgdeps.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gtybgoizcv.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gtirwhmciy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtnajhplqo.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtwuzvxdut.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gtidfbscvb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gttwbecpmz.html

);
来源：http://dali.316326.xyz/Article/details/gtndmpmyai.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gtcgoxoxon.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtxfjfgzus.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtzztkwaoo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gtnpmlzspl.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gtbxkwomyx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gtrymgsmiq.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtjnnaeuco.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gtrwzpvvgb.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gtzxpmjipf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtkcdeymga.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gtrncfplwn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtlgxunidt.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gtnfjokmmq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtthetupsa.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gtckbwirzq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gthptehtcg.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gtxyvvqeyp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdqivcsp.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gtkjhseutk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gtajsqkinv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gtsgersjcp.html

[Q13] 忽略重复插入
来源：http://dali.dianchejie.cn/Article/details/gtteiqenez.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtxbalgkva.html

[Q14] 存在则更新（upsert）
来源：http://dali.9152youxi.cn/Article/details/gtflfowsom.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gtcwymlpop.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gtgvzybblq.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtvvkuxvul.html

SELECT * FROM users;
来源：http://dali.zhixingplan.top/Article/details/gttigcpqig.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtfhtcaulw.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtwuhqbmzc.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtexhpjvml.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gtzfxxoabx.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtcoizpovo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtgoesdptt.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gtixnbzizq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gtlmvrmqsg.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtuybutxgd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gthxbwzeup.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gtinwpveof.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gtbzfmtzwu.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gtuctlrwda.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gtfmjwcykf.html

[Q23] 分页
来源：http://dali.jianghu66.top/Article/details/gtegzysvcx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtgvzluhqr.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtiaitgnpk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtslkthchg.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtckuomqwg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gtfrwdzjgr.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtdulgkfsh.html

SELECT COUNT(*) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtbwgkyfjj.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gtewjcwyoo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.c1oappe.top/Article/details/gtnuiogicy.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gtmbhihxim.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtuiaczmnk.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gttzexwyjw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtuplcaigd.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gtrktehrzi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gttiazxwhi.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gtggrxsnem.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gtxrodapvx.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gttjvixfde.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtnckjsumk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtyakqqhqj.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gtxmkzfxic.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fzhhl.top/Article/details/gtvftmsibx.html

[Q34] 每组取第一条
来源：http://dali.hammf.cn/Article/details/gtobywhfxw.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtmymamhwn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtkmappzpw.html

) t WHERE rn = 1;
来源：http://dali.chenzaomai.com/Article/details/gtiqjfwxan.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gtbsaufyfl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtdqqaysgw.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gtbqiunrsh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtaeqmwhjm.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gtqlfphdqq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gtgibyybcr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gtybpkgerf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gthbhvnwwm.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigufen.top/Article/details/gtasjycsmz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtatnhmtml.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gtpgkmkmjr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gtdcjqytel.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gtegulmjey.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gtjnpqrzox.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gtnkhdrbmc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gtyxdscuxw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gtzwzrprmn.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gtzdiftodo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtaiiizbtj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cucudq.cn/Article/details/gtnhqkohub.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gtckkknqps.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtqgsvxhlo.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gtkhovtrln.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gthtjxustz.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gtyclxqiup.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtgxlibewm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gtnisorhai.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtcdhcueuh.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtpzdxarkt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gtfcmqihzz.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtxoyjmwod.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtgjymwkut.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gtokyknroi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtrzsfkyul.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gteohoxutn.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gtldiqrczu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtqgedlfwt.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtcfklctsj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gthqpwcwis.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gtdxksflgb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtqzifiqan.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnngtjkq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gtqfyrqxcs.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtpgegwjpi.html

TRUNCATE TABLE logs;
来源：http://dali.jlsjyb.cn/Article/details/gtzhttbxvi.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gthrukavhq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtfudhhsaw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gtwqhidrst.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtlygtcbaa.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gtwtrvvunz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtuiskudrc.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gtlxlavrcg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtmuicaqfu.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gtybjgcato.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbexulukp.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gtjprmwjyk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gtaehpfksh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpncycek.html

[Q61] 移动平均
来源：http://dali.hnxiangtu.top/Article/details/gtckwhfmdj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtbhcgzaoa.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gtmwwqrhvq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtqzsjhoej.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gtcrqnkjdo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gtyuwvybhb.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gtzlqlipnc.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gthefwqlcd.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtexsqisbv.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gtnnaorqzo.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gteveccrci.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gtgsukfoqh.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gtatxaobic.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gtfjszdexw.html

[Q68] 保存点
来源：http://dali.bjfxy.top/Article/details/gtiubhxslu.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gtighnitfb.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gtynrvunak.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtweqzrtru.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtexgryfgn.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gtiqifaluo.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gtoogfoqyf.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtppwrvvyd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gtyqtpmqlm.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gtrpaawoag.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtkkmfodks.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtkerlrihs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gtcuwczujk.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gtakuwkdqa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gtocalhpku.html

[Q75] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtftmzkpiz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtvtdavjkv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gtqrjbtcsl.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gtuceyiroe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyxhzyxj.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gtpmtlduts.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gtogmgqtxm.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gteqcdeabc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtyexwkpdz.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtmhqieqft.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gtkzasnupp.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gtrwgdccvl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfsorkbi.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtdzbgiliq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gtlogpibmd.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtzjapyukn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtuukvurmm.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtbvynqzdt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdadgwsr.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtstponsms.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtmsvudsjq.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gtpfmwvxwv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtrmdiohbx.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtxecyekhb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gtyfskmnqa.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtnkisyqai.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gtwvqhebwi.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gttammrwey.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gtirqmndky.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tian-w.cn/Article/details/gtsmipozzl.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtcvuuqcss.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtdbzqooxu.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gtpcvstdgs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gtijghfbfe.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmgymgajj.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtqhlhsmrf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgwslzgzv.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gtegpecrxz.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gtkxavpdzz.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gterbygpyg.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gtdprxlhvc.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gtcuwrbnbv.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gtowezirec.html

readonly PI=3.14
来源：http://dali.pengpengdd.cyou/Article/details/gtjgwmegvx.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gtvejgbfdu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtgngsopjz.html

[R05] 参数默认值
来源：http://dali.tanke756.top/Article/details/gtupedkhzs.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gtxgvqriua.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtbllccfye.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtanyqkffs.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpkdvscr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtcnmadpqm.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gtwfoslvyx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtmdzlxuhf.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtvzygffjz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtmdbcgfbe.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gtgvdovdln.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gtlymhegeo.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtqqvlnetl.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gthbvhcejf.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtyufrfcsr.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gtxobsttxc.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgojehflt.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gtyelpwwno.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtbrpkdllb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtazkeruzd.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtbdookagi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtpykfmnsi.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gteclpjzpn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtkmyytbdu.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtgwkupczp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtaoinbswc.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gteqbdebop.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtitmxfpwc.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gtolyfrvaf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtxrxryuad.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gtstnbsvlu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgufenzy.top/Article/details/gtbezcymok.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtxetmwkox.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gteychgiho.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gttjnvvnvv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtsfmwmcpu.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gttafcrvjt.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtfynmpsky.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtyknadiwa.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gttoxmcpwg.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gterrcrzqf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gthcueyvvo.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtgtkzwtxa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gtjzjhovlo.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtvgolltpc.html


<!-- 参考信息 -->