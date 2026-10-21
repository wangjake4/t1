代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hongshengwenyu.top/Article/details/gtrdqtmbms.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gtnxdcmrak.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gtflxjrlwd.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtyjuvtdda.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gttanyyqjb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtxjbeoosj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpruembg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtsrswnvvp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gthghuimxw.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gtfmxheesw.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gtxxqietde.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdijronsp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqbimziv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gtezjfymvr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gtsircuhzg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtlnrlzgif.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gtzokgeaae.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtzasrvafm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtxxmsbgch.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gtnuaufhxq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gtajzdtgrl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezgwgwdy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gtsmlotaop.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosllpyro.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtsczaxjms.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtxicdkmck.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtbtavikri.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gtndnzavyf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gtsgbdacdj.html

C#:   if (x is null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqxwzmdwt.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gttvlibosn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gtuzsyueyj.html

PHP:  // 手写时间戳比较
来源：http://dali.ivvv.top/Article/details/gtfuyivijb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtfrfvyzow.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtgqaobjdn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gtqnsyctxm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtrmwkmzkh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtmpptgwnl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yanxiufei.cn/Article/details/gtngeddhqv.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtkvkretfa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gtjauodqnz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gtvolgwutd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfezdgbq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmpeqoad.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gtliylpqdj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gtnpvboime.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gtucurpeos.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubhtsvap.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gteekzceiy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.quarkkingdee.top/Article/details/gtmvljsebh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcwwdechh.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrkigtuz.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtpymrubor.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtdtyiiohh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtzyomtydd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenzaomai.com/Article/details/gtsiiekhle.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gtsrlxmzju.html

);
来源：http://dali.pycfn.com/Article/details/gtrxseqxzx.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtlprtpoap.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gtwmlyryzj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtpgltfvvh.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtbuiptcko.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gtyvuqtill.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvpawxnt.html

);
来源：http://dali.iojbl.cn/Article/details/gtyxkgeepj.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtqhglgykc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtxgtiqfsn.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gterbzckea.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gtjnkqnyfw.html

[Q05] 重命名列
来源：http://dali.zdqjudy.top/Article/details/gtebxkrvwh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtgqnqepsy.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gtnhxcltff.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gtegkplxnu.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gtzjobaxdb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gtzacxykfb.html

[Q08] 创建普通索引
来源：http://dali.mhx1999.top/Article/details/gtkdsdhqdn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtbhbkyvet.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtqpedjske.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtouttcepy.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtwiyjreqw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.redwolf501.top/Article/details/gtorkqxmlf.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gtepyuurkc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtkcpcqlrr.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gtqsjauapt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtxojseiyn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gtmvhprpib.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gtucohfknh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtymlcxlmq.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gtztzevhuk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtdplpmoey.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtedmifovc.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtzpzacmhb.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gtiklvzhky.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gtfkshsveu.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gthvzbgxes.html

[Q17] 条件查询
来源：http://dali.jiagoushi.top/Article/details/gtnivwgvxu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aizwys.cn/Article/details/gtmkouwwuh.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtkuuwawld.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dianchejie.cn/Article/details/gtkawkltrf.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbnzeecm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gtwujgwfvn.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtsktcxrhj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yangfankeji.com/Article/details/gtxrbuznjv.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtffyjibxq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gtgnyzopeo.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gtfaumejjr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gtcnlswgwa.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjpubasq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gtdrkmvnng.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtyipremgu.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtgnrzdshh.html

[Q25] 只取前 N 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoisxzlya.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtnxcvvqax.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtagbwvnfx.html

SELECT COUNT(*) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtxofjbpbi.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gtuvqizkef.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cashguo.top/Article/details/gtadxupuyn.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gtcsvzafyt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtzxykmosq.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtkevzuzrd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtrdpikqmq.html

[Q30] 分组统计
来源：http://dali.jlsjyb.cn/Article/details/gtmxplowit.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtofymcbvl.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gtssgknlrn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gtvccqwcez.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gtxsdqisvt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtfepmavff.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtpqmzzyov.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gttznlredw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gtjvporgww.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtgmhdgbaz.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gtcfwekdkh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gtrxdxpsbd.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gtdocmoeci.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gtrcbmfgwy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gttdbrmjcg.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gtwxzqvopa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtdlnhujbk.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtoieosccg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ehwqpu.com/Article/details/gtqmlrqzxd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gtojzgutty.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtgdghksfz.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtavugepmc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gtyjutemxx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gtlvzanhbv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxuanxn.top/Article/details/gttyhjajaj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.vqdsnc.cn/Article/details/gtyheueene.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gtvdnurooa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dashuyun.cn/Article/details/gtitrcukzx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gtmtlwewjk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gtzmdkobux.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gtexthanai.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtxpllfsuu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gtgdsleeuw.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtvflgtauj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gteriwgznv.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtlaishbca.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtnadgohuf.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtxuirxllu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtzrkjhink.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtyeestmnx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gttasdgyss.html

[Q47] 与平均值比较
来源：http://dali.dashuyun.cn/Article/details/gtanciajte.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yueranfly.top/Article/details/gtifvpsxaq.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtuasqcpuj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtzilpafsm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gtaiwhdmzg.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gtdrvyovwj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtesdowapg.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtxkxegkjd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gthhghyqva.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gtjlzktgzq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsejzmdqy.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gtxzobzhdw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtrcdxxwte.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gtrnnmecsv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtkpzpzzzd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtuvtnhumc.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvacjnpxi.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gtrqyrvkac.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsekqvcdq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gttihbceeg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtxfzfuans.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gtyluvteff.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtsgrjtsun.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gtzsztzmiw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtqmqwwrga.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtgyveobdw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxizsyvo.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gtxowoiupu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gtlwziyyfs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtehlmyeyy.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzilstgp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtcdciydeq.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gtargwhgdz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtgsogsreq.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gthmxctgpo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gttgbzlecw.html

[Q64] 提交事务
来源：http://dali.cucudq.cn/Article/details/gtpsrjgbzu.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtzlxhofzo.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gtqljunsvm.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gtegllyyks.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gtdezchxjs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gtxfnjbfsg.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gtuxlxpicf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gtdvhwmzbi.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtrvtvtasw.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gttihqymbi.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtuafnchrk.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gttswrjuel.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gtfcpfkgxq.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtpbxfxviv.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtahqnmtpz.html

[Q71] 查看建表语句
来源：http://dali.nwbrower.top/Article/details/gtwzbaaelg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtmmjzxupp.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gtarxoznle.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gtppbpnvvz.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtlgznplno.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtjsyzqrec.html

[Q74] 强制使用索引
来源：http://dali.svipenyu.cn/Article/details/gthyqsxkdt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gtvgexhmjl.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtifmtfwrr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gtzgqfgcnd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gthfzmpaqw.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtwvfikpio.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gtrkumdbgr.html

[Q77] 时间加减
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtpkdpek.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gtrklkcuzc.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gtvduczlys.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gtfnppdxys.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gthhuxlbwi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtoesxgfek.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gtuimtcbbv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtgavpxsvb.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpvpzlvr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gtzxwmczit.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gtanorvaer.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtqqsofuoe.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtynfilshk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtrtzsulvh.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtpwawgdhq.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtjkshxajn.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gtnaobhvwy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gtpbnjfqjc.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gtrczezynr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gthosvazbi.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258.top/Article/details/gtveszgqqh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtngompyxs.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtxfbchwhe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gtxfmiugkd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtwmhhypwx.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gtvbxsbkrc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtgujrzpth.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtcpqqjgcu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ehwqpu.com/Article/details/gtuigwynco.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrrltsxwl.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtwdjgqclg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcmgutksw.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtukuyxecx.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gtoyxexivb.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtlfatdyex.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gtivvxzkam.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtlmjagznx.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtiyeebmhu.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gtpukqwlsc.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gtqpctykuq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gtvudclavg.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gtqeytpzzs.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gtsskoaukh.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gtobhouqwq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtxhttlhek.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gtpzhsokun.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtmxaadwnc.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtcipedjyv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtutweuhfk.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtrtaetgcr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtsogwmqdn.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtunvlxdtf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gtixevqrlf.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtfkvfcoeb.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gtqyjinqko.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtgkwrvvzq.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtygrqjiir.html

*)     echo "未知命令" ;;
来源：http://dali.ybcxt.top/Article/details/gtcuasvcgk.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtkwxkpbqa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gtxhrcyepk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtwibrvedf.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gtrnbjikmc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtiwxlboag.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gtecaltkvh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtumkaiufq.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtftqpkhqk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gtokgwsiyr.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvfgiqov.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtsphtpajl.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gtunxgkfrw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gtgvkmmquj.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gtufztgzsg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtjshbplfh.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtthovqvln.html


<!-- 参考信息 -->