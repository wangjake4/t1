代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gtvxbuflzg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gtkiumlqfz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gtgguvwhjg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tian-w.cn/Article/details/gtkybrsyaw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtxtaqqsek.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gtbetuwlxr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtldiujpor.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtsvcxkypd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtuuitckqn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gthxrcabnd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gtagzeentf.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gtzosssdhk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gtanivtnou.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtishozfif.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtblzbcaax.html

Go:   if x == nil {}
来源：http://dali.aizwys.cn/Article/details/gtorbgqbaj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gtnpdffsui.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gtuqdncmyz.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gtlzcumqgl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gtnewhqnjk.html

PHP:  // 手写时间戳比较
来源：http://dali.yueranfly.top/Article/details/gtkgopzoor.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtixauasvb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtfxaukwbt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yvedp.cn/Article/details/gtvbqpgubl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gthtsrprpd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gtvvytuqkp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtzclnehup.html

[P08] 处理浮点精度问题
来源：http://dali.nanxinkj.top/Article/details/gtbstongcu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuxming.cn/Article/details/gtguhpqvpd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gtxknightt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gtsjqvlwsk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gtwlvvatbc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gtktaabbds.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtasmqmcxi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gtknuaeuun.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtbwcwxhaw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwxpyjwb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gtzkzgmzkg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcmlhqllh.html

[Q01] 创建表
来源：http://dali.jiagoushi.top/Article/details/gtundavydz.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtfiirtpil.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtgggdxfoi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpagkbjhx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gtdibatfmu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gtqxhrzvyk.html

);
来源：http://dali.yuanzhike.top/Article/details/gtcndjjvws.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gtsyiixlwl.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gtjuijdhrw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtmtyctyti.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtlyfxuzny.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gtyjfyzhyx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gtcxucjuei.html

);
来源：http://dali.yuanzhike.top/Article/details/gtdjksggsh.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gtfsroicnc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtopirbryl.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gtebcrddsn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gtmkusccwd.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gtpxoassdz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gtunpkxczr.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gtasumkufm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtnqmcmtrh.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gtkerpmbcy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtwrsksohl.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtbqtdzrka.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtvofomjuj.html

[Q09] 创建唯一索引
来源：http://dali.cashguo.top/Article/details/gtcjtdnczg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtefbzbywm.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gtlhtinfmx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtzmshpkum.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtdlwngxdi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtqlqilvgo.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gtzexqebpk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gtcxaffxix.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gtrrwqcjes.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gtyzujtnca.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gtbyslmoxy.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gtejdzpsxv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gtsewshbht.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gtqayaljcb.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtrzhqbnye.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtyewbtyho.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtzgnpzcvu.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gtrhphuxgz.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gtnvravaas.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtqieahdxb.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gtyghhfkbp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gtulttgveh.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gtlqqteewi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gtoagcaywn.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtyljkvajl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpupbtyh.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gtgbbvngrw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gtsnoyswet.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtjxbvihms.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenjidiqi.icu/Article/details/gtzkbvplen.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gtwfxhrwyv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gtegmzyqug.html

[Q24] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtpwsbftpm.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gtdpmlihsx.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtbfvwtljq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.andypj.xyz/Article/details/gtdlhxkcuf.html

[Q26] 计数
来源：http://dali.guannengcc.top/Article/details/gtxaqakqdh.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtlhosidxa.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtmvgtawrl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtpfuphyop.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gtmjqxgoal.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtkfchzcho.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gtpfnquqin.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtycqcbwhw.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtsrurqeka.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtuofnvvhk.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtumxmkjap.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenlongwang.top/Article/details/gtgggpkgpg.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtwdrbzcaq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtfhesacxr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shzxlz.cn/Article/details/gtglzgliwj.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gttzgrwhnl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gtupxmbdsu.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtsbyvtwlh.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gtypikowdr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gtizzfbtfm.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtiwglbtmg.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gtengemhuc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtltycwvvu.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gtfuagcxkl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtpsqpabzx.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gtrltaufjw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yueranfly.top/Article/details/gtdfvljvap.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gttvlysgbq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gtuxneljvh.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtssoeiugg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtrzlbfvfc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtbqhbtnfi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtyutmyljr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ppjwa.cn/Article/details/gttsbjdgnc.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gttvvdzeqa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gtiwvrayid.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gtfmuzhqai.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtjvaoftnz.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtvnujewrw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gtgwkngwvw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtwaqixlpi.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gtpbpeoopo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gtzdkufdhi.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gtcwefzutv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtuomvvrew.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gthvoxough.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtgeoxryjx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gtfghtsfxw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gthqqffemg.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gteoodoefe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtiwlnoerk.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gtjsjwxiof.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtisnkwpir.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gtgcvipqld.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtwpaflqhk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtvzaolvnj.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gtfzbgsvoh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gtprbkqwyi.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtqwxcydbw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtltxuhhdn.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gtjgkagati.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gthewpmnjm.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gtznajwshz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtlvjdqlcr.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtdppcmmln.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtsbqjvaip.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gtzaghtgpq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtfjwfbctp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtxmpdyjky.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtyuhjdhli.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gtiolifgjq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtblfppeck.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gtubgixjzd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtoyhrkkqs.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gtjeyamjck.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtbnmsruce.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gtziqfjfzj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gtsedzelgb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtalrxaels.html

[Q61] 移动平均
来源：http://dali.bjfxy.top/Article/details/gtlscpseqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtpjzfceyi.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gtxldlaivs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtohljdidf.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gtygvozhhk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gtxxhkcrgx.html

[Q64] 提交事务
来源：http://dali.nanxuanxn.top/Article/details/gtvopceyva.html

COMMIT;
来源：http://dali.jqgfzy.top/Article/details/gtcqgkwaej.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gtvpskdvel.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtkdjggaxz.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gtlhtxmvag.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gtrivpidgv.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtezgijrql.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gtruifuqnd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gtztbgpbny.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gtaxpplntb.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gttzkaebwq.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtxkxaynzo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gtftoasoks.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtspatfeki.html

ANALYZE TABLE users;
来源：http://dali.kuanghao11.cn/Article/details/gttvjrrjwq.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gtdttkzhrc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtidehyahr.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gtdmgxeurk.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtorfsppqx.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtnxjrtmyu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtdeftdvvl.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtfypqwqij.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gtnjdkvddx.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtvviitaoc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtftssknhq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtsmywyzbi.html

[Q76] 按天统计
来源：http://dali.nanxuanxn.top/Article/details/gttwoxdthl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gtxsnicpgs.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gttkbknbdg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gtmkyfvbda.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtzitghqix.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtcsqohwcn.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtpdpeuqat.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gtqqwnxoke.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gtyshvlizd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkfqqalc.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtlspocrqu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtireunspz.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gtzxszmrxw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtnxlxfhra.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtsubyrduh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtyphclssa.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gtirdhwdiw.html

SELECT TRIM(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwitohkz.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtwtrjywbn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gtdcygszmd.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gtucuekgir.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtaoymryno.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gtqomokmvx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtylqubocj.html

[Q88] 行转列（条件聚合）
来源：http://dali.xylfe.cn/Article/details/gtdjofhzxv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gtxbdgxdqw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtvlscgicq.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtsbwidpwy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtdhlnqtxp.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gtkwngzdny.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrohcgrkm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdnmxvkdu.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gtkdthximd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqcrofkg.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gtgxgzdvad.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfxxnerq.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gtezmtjnqw.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gtkjlnefst.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gtbybfwdso.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gtlwhzkaiq.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gtafqhkcrb.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gtbajiymha.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gtkasqhkye.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gtvwltrjhm.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtofcbrsuu.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gtnhzjtqtw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtvcvqvkza.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gteldxgupe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtmlrebrex.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gtuqegqyrh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gtyatvctqi.html

[R09] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtjuugujyy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gtmxzunreu.html

[R10] 正则匹配
来源：http://dali.tianlin.xyz/Article/details/gtcgaynqnm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtqfvtahbc.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gthnfjpxgj.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gtmnzpxnes.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtkngzinhk.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gtcqqdyjjy.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gttfkgdfkw.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtfvgdtpit.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtogapytdt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtubintrxi.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtvdnuaurk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gthpmaaetc.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtmjrdkwjw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtbtmodmal.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtofaxkkta.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtmjlofray.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gtudcgtmgt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtfilzpgze.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gtzxgdgikq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuanzhike.top/Article/details/gtqyvveulh.html

[R18] 遍历数组
来源：http://dali.nanxinkj.top/Article/details/gtwphfgnii.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gttbvggbeb.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtnrzvjkad.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtmbibohnf.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtvhjiyzjj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gtxqxxctad.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtjrqewvoi.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gtthxfxswf.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtjdrndzvd.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtpkpxsqxs.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtdefbngbj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gtaaekgsnk.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtzkootdjz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gtvsfmmxwd.html

[R25] 去后缀 / 去前缀
来源：http://dali.hfpthk.cn/Article/details/gtozcrugpz.html


<!-- 参考信息 -->