代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gtltvkfovm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gtztcfwpqe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gtioevjaya.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyqwsgyd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtzrowksfd.html

TS:   if (x == null) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfmqsmwcl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtbcajcvuk.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gtctnqmxta.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtqdljivxf.html

C#:   if (x is null) {}
来源：http://dali.kuanghao11.cn/Article/details/gttynrjwrs.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gtlflyyapn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtvvgpiuec.html

PHP:  // 手写时间戳比较
来源：http://dali.gotoacloud.top/Article/details/gtfipqbiqv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtmwbwdwtz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtctzazgbe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzlxeehie.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gtjicygwra.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gtbjypbgwk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gtlvwomabg.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gtgctmeyqv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtjaulkfav.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtzkytxqka.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gtvejfttzc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtpizejcdz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gtbdhijpsw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gtdltmbupi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtoyiooluj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gtfurtmenf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttfotibve.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gthdrvvqhk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtyvmausoi.html

[Q01] 创建表
来源：http://dali.jinqigfzy.top/Article/details/gthfboufst.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gtoapvnnvb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtebozhqim.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtoouemouu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gtthtyggra.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.0kj1m.cn/Article/details/gtoxughbjm.html

);
来源：http://dali.0kj1m.cn/Article/details/gtjrtypjla.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtfgjuwcqj.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gtwfegxldn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtfnwgvuip.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtqfojrctp.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gtipgotvgt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtzpttmaym.html

);
来源：http://dali.dianchejie.cn/Article/details/gtaeiebrvc.html

[Q03] 增加列
来源：http://dali.jinqigufen.top/Article/details/gtqsudefdf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gtxqlloefb.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gtgfnbyyyj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gtwtyxmgvp.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gtuyaqwliq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtxwksyciw.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gtyapqmjjj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gthuzbgfwi.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gtfyoyxtfd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gtmggwiiyv.html

[Q08] 创建普通索引
来源：http://dali.shzxlz.cn/Article/details/gtcscizgxb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtaagshemx.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtanqeszgs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtqilnkmaa.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtieszktnv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtzutlposm.html

[Q11] 一次插入多行
来源：http://dali.yangfankeji.com/Article/details/gtgevldgdp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtjmcrfimq.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gtivbnmbpi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gtnzvmmcpx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gtxsyhuvsh.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gtsazynbjc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtszvnmrdj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gthylflale.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gtcybvlssw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gtugldipjb.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gtcaflrjcb.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtyfnckejr.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtxnrsnjho.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtdiedsukn.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtkdrfuvlj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gttwgaycpu.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gtsjucberu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gtfvbfmyxl.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtqmabprvn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gtisbkntsx.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gtvnpwmcos.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gtgcvrtfmh.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtichfswup.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gttxmqffuj.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtagehfmnm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gtujxjllgi.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gttxtjhzbk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gtarlchaft.html

[Q24] 去重
来源：http://dali.ppjwa.cn/Article/details/gtlvgpewoe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtkzyaypft.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gtpihrkexk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gtoalgvnca.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtzksswwry.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gtlrkyllle.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxqeztcb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtrzccteer.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtmohucumc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplagepws.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gtnyxsffxa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtwhcttksv.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gttsdytgoo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtcuvvigfp.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gttafrufwp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gtkcohavlp.html

[Q32] 分组拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtqnumgdik.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtutqsnzeb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gtixgjwkvo.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gtmmelskdr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtpsrunhxn.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gtomukuicg.html

SELECT * FROM (
来源：http://dali.tianlin.xyz/Article/details/gtpoumxvbp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gttmazcczh.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtctizcwac.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydgjeiiu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtfqfcczlj.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gtowsfhomn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtulfhsdco.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gtlquoqutt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitribfbj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gtmasdhdzh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtksshlvfa.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gtavdyvrlu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gtoltquvhp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtazctdmfu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gtuxhggupd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtcsaasgyo.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gtdhnjslup.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gttullfmwx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gtahqfvtdy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtyjsamepv.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gtvbrqwglm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gtvtemorfv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.0kj1m.cn/Article/details/gtwnzirrdj.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gthcqcxhmz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtbwppwh.html

[Q44] IN 子查询
来源：http://dali.snrcjt.cn/Article/details/gtupjtstab.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtusbrrvji.html

[Q45] EXISTS 判断存在
来源：http://dali.daxiang520.top/Article/details/gtncyzywla.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtiyzugjkq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gtmeaxkvkz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtxuldhfqx.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gtkdhvkayt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtlitewpqr.html

[Q48] CTE 公用表表达式
来源：http://dali.tanke756.top/Article/details/gtdrlcwflw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gttfnbxdoy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtjqjdlnjj.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmsvcaql.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtfhqvbmnd.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gtyotojuqg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtnuweynbd.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtvwlbjzlb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtvlpunfry.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gtabjnfkki.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gthlzconra.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtzhzbdyyr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtbitmacms.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gtuwbwuloc.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gttpxcrwwc.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtqnlcklbq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tanke756.top/Article/details/gtelzhigyl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ehwqpu.com/Article/details/gtfmfckmpx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtourzdyuk.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gtvpvwftqx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtsbswnwdk.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtmmgerisp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gttgtkbhkb.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gtlzspuzdk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gthbagbpyo.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtxbgsbjyr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gtafpeuchq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtkmgynwlt.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gtegtslcpj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtdpynumsz.html

[Q62] 分组占比
来源：http://dali.fzhhl.top/Article/details/gtiddwmbrp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtgrtdkrvo.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gtuyzuymrg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gtmlpzncen.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gthruxvmkw.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gtopobbzuj.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtfntdoguz.html

ROLLBACK;
来源：http://dali.cdnleiting.top/Article/details/gtqxetrjgw.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gtislwwxpd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtkicvpmgf.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gteawqlhgw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cheryme.top/Article/details/gtcdaefykm.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gtnulytsif.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gtloboserf.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gtpgmmhvki.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gtndzharzu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xziqi.cn/Article/details/gtzwsrveex.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxzoklhz.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtrgohyvis.html

[Q71] 查看建表语句
来源：http://dali.haohaochexian.top/Article/details/gtksholcrx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtmffvitii.html

[Q72] 查看索引
来源：http://dali.ppjwa.cn/Article/details/gtnxzeiqrr.html

SHOW INDEX FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtqdrswlfw.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gtohhrcjbq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtiravvbyx.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gtfdnkxnkc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gtpajinlhr.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtvpnbenjz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtcvvqwahm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrccdvma.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gttaerepik.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtwvdoozrb.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcrgdleo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtgrpmghdp.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtdtdjiteb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gtbvkomzqf.html

[Q79] 字符串拼接
来源：http://dali.yj20258.top/Article/details/gtxforrjth.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gtjvxxmaey.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgidbubz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtqvongvwa.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtlspygiwk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xinyue.icu/Article/details/gtofarbdvo.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gtfuiceuuz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtyigdjzwb.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtectliupb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtxqxatiea.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gtngptcxuc.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtgbjxigti.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gttouepryw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtxoahienl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtwkokbpkj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtjxjoybuh.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gttjlezdwj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtxjdqgylr.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gtaxnaocji.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtmfhvkaoc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtnvjvmfey.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtcgdmlmys.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gtetbzangs.html

[Q90] 生成序号列
来源：http://dali.tianlin.xyz/Article/details/gtpjmzgcch.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtyxigcclw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttribigwf.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtajaqwfbm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtroyuapnr.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gtknrpjwtt.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqlogmeb.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtnpenloee.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyfjylut.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gtgrgpdzoj.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gtgcfdjkem.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtvikmmxyi.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gtzwoegkcw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gtbfiqbhth.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gthuxpxwpu.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gtslwqhamh.html

[R06] 判断命令是否存在
来源：http://dali.zhengqikj.top/Article/details/gtzrjjhllo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtrzzpdnpd.html

[R07] if 判断文件
来源：http://dali.xylfe.cn/Article/details/gtyocgspdp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtymandocx.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtjhplgfqb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gtdluenmrl.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtjrobonmd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jianghu66.top/Article/details/gtbynnueqb.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gtnvnxwuof.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gttmbphokt.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtkqwgguaa.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtspvnslnz.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtyzqagrqz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtpdahhrbw.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtztnxxrmb.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtgholzptp.html

[R12] for 遍历文件
来源：http://dali.yueranfly.top/Article/details/gtpronfdmt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtnmhlgyzf.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gthtxvoxyc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gtyexygegy.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtyccnlkvw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyizrtadc.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtlfayvyti.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuanzhike.top/Article/details/gtblxzaoyx.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtwpyfksqr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtqdodtkdo.html

[R17] 数组定义与取值
来源：http://dali.zhixingplan.top/Article/details/gtzrmhgehd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gtbrscmveh.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtweigvxhz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtzecnhbry.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtcbvmtusa.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gteyfwndtb.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtbneutvlf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtyqmdjasd.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtnnadenad.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtdfnaztic.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtiismgigr.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gtfufnecxf.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtvvqltjdz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtashduucl.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtjfkjisgf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtulaheceq.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gthifllysg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gtwkhwdmqw.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtojkbupod.html

now=$(date +%F); echo "$now"
来源：http://dali.ehwqpu.com/Article/details/gtfptpuncf.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gtzrctyrpc.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gtkcjryyvl.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gtjyotegeb.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtjydnevrt.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtllphkpvb.html


<!-- 参考信息 -->