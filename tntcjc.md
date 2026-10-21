代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gtuorrquxf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gtplrclkhe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gtgfkxvbzm.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoapmmwlu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtghvhubgs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtzhgoejiz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtytfinltt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtyjmoofkt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtrknehlvh.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gtbhthppwj.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gthdwdykpt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gtbijbdmdo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jianghu66.top/Article/details/gtqdtxanek.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yanxiufei.cn/Article/details/gtvwkpoxlj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gtgftnebvy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.316326.xyz/Article/details/gtemdtkmqp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtmiuergkf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gtmtdxwwzz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.mhx1999.top/Article/details/gtcvrxfggp.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gtsmkttlqy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gtksmmrtct.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gtmtpitzkd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtntisxsyn.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gtkehiyixs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gtymqkdqzk.html

TS:   if (x == null) {}
来源：http://dali.kuanghao11.cn/Article/details/gtiaokmujl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtniaessda.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyjmgfcr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtndvpsewc.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gtbppmsowq.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gtnqdkwxeo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gtcluhunzs.html

PHP:  // 手写时间戳比较
来源：http://dali.cucudq.cn/Article/details/gtklutobls.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtvemnrjuu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtjlrpizbs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdruuylpp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gotoacloud.top/Article/details/gthxfcnfxy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gtbyhdqcbh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gtpoomrhoc.html

[P08] 处理浮点精度问题
来源：http://dali.gotoacloud.top/Article/details/gtunjutcuo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nwbrower.top/Article/details/gtsmjrcgxk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtiarsioew.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gttygvmxok.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtmuzkupcc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gtjhzjzhva.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gtvefnvmyh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gtsicvmrsv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gthnldsnii.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgvkrdavn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gtrwhzzwkm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtioawbrfd.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gtypgftczm.html

CREATE TABLE users (
来源：http://dali.sufxvd.cn/Article/details/gtpnheefik.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtarusaoxv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtdespoovp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gtddgahvmg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gtyktrnnkn.html

);
来源：http://dali.ybcxt.top/Article/details/gtwqvsgayn.html

[Q02] 创建带外键的表
来源：http://dali.chenzaomai.com/Article/details/gtsspamxpx.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gtezumyvxw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtfhevucuk.html

user_id INT NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gtqhlnylvj.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gteshccolj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aibaodan.cn/Article/details/gtkxxckpny.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvozcmspl.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gtzefhlgkt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.snrcjt.cn/Article/details/gtxvatojku.html

[Q04] 修改列类型
来源：http://dali.gaohongyu789.top/Article/details/gtvxznlnzc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtchcxoykl.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gtpsholync.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gtaofyhqkg.html

[Q06] 删除列
来源：http://dali.guannengcc.top/Article/details/gtdwmocvxs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gtckuwhfpo.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gtuafnvznf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gtcgbobqga.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gtpxgtnxdz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtiisecmar.html

[Q09] 创建唯一索引
来源：http://dali.jlsjyb.cn/Article/details/gtbpbagokh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtzfyrstsp.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtgfubmuzh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gtpsndcbkt.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gtwfsxkzmx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtzhnreubu.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gttqkvlhnr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gtdgeodoye.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gtrihuqies.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gtdtuewbgw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtjldhwmlw.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtjwovnuak.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gtbpaqazxl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gteekwapwm.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gtqcczrecf.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gtypeqizjk.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gtcagrdewp.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtalmpqiqk.html

[Q17] 条件查询
来源：http://dali.cucudq.cn/Article/details/gtgdvvmeqq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtzpjicubk.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gthngqvuco.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gtgsseoopa.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliqpjkbz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gtokwecgxb.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gtipqkzjrr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gttreyiptv.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtpjzxzpgx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gtkkxsyipv.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gtytirjwzn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gtuidycgcj.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtggpjkdsr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gtpcmdnqne.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtlcctljsj.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gtadxikwke.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtkbixvttx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gthfuyssjq.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gtsbvxgmpq.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtodiephhx.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtgwyaltpo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtvfxgspua.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtgbqfvpfq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gttzrlixzz.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqytmmxy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtzjlmokrf.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gtuvakdzly.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtalevjpsi.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtvxzcnsoe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gtczrlizyw.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtycsinrvx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtnplcjzwb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gtkouuzzvu.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gtwlqdqowp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gterlrtuiw.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtdmudcvaa.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtuaoytril.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gtqfnwsrlu.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gtszozhqjd.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gtdhbpjbjq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtdrkertzc.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtbyprkfiq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtegkthidk.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtjlfrqiss.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ppjwa.cn/Article/details/gtbisaddxq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gtchlfhucv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gtmefhgtum.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gtzljfttam.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gtvpxeghic.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shuidangran.top/Article/details/gtymhzrnyx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gtcebqztnj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gtdjrncudt.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gtrwrbxtxm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gtgqjknpeb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gtuzyazmdq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtisozjnta.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gtosmaswfd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ybcxt.top/Article/details/gtiuxcmiup.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtazeipmew.html

[Q43] 标量子查询
来源：http://dali.nanxinkj.top/Article/details/gtoqfjsdtc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gtcdekludl.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtzhqdtrho.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gtybblvmkq.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gtalxxyzur.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzajjoat.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gtwdkctwga.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtczuosueg.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gtstdujokv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtfwvtgbhi.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtwbwjirji.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tian-w.cn/Article/details/gtkgpwdudt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gtpgefhixq.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gtwljijgpw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtwnrfpgqx.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtqqkdblsz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtrovyxmeq.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gtkselfqls.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gtfghgddjt.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gthqkpoazd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gteijdrxvr.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtakwsbnur.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhpwvzvn.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gtyzaakqsk.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtcrpbuhii.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gtkotlmorg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtxoplpsca.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gtcsafiqgg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtasbjjdzg.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gtpwpkfvwl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtbzjbjbrl.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gtoogvituo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gtfpepvafn.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gtmogttrxb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtlopwzdwy.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gtpqekhnxr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtjwfucmep.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtqknydwpe.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtpcrzlnes.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtujwholtt.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gtlghlmthd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwsdzbdi.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtmvtcoexh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gtdredadsw.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtrtaaxzug.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtoffkcsto.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtrwrerzls.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gtckqxioii.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtufahlnov.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtxzcbkors.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gtmjbwyslc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cucudq.cn/Article/details/gtfwqytqvm.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gtimybhiqv.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gtrlvmrgsg.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gtakjyzuae.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtketmqtkb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gtmkfalkan.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gtzvapbtni.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gtycuvqtut.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gtkqyotxsw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtuqjekfrd.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtcxcxnexy.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtpzlywvvp.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gtfkeumtrx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gtigabubzf.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gtvwwawuie.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtlinvdtej.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gthjpxukfe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtiokcqygm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtiocoefqz.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtvwhmetfo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gtdygrpmmy.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gtpqlahamn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gtiojsstuv.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtntwgpcqk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtermnfvtg.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtqklrwczj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gtjpazxkbp.html

[Q80] 字符串截取
来源：http://dali.snrcjt.cn/Article/details/gtayflebmy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtiuhsgwey.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtrijzdqcw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cheryme.top/Article/details/gttbkkjorb.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gteshsgylg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtfnyvvekx.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtjbtoxpqt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtpjrexquf.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gtzimqqibw.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtopdvkcri.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gtsuwqenci.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuetiantiany.cn/Article/details/gtynbnqyfw.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gtvowpvvwk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtgjuuexvs.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtjkvohwej.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtrryvguev.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gtkauxknoj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtiqmbkxzq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtxyfgzrjw.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gtkhvkowjz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gtruieilnc.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtijlmywbv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gtakwwzfic.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtnmxvwjgi.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gttqynhpyl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjrsvgejo.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gtezctqzbl.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gtssgivgyy.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gthwxqkfau.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gttnvbysgk.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtdcwsjthh.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gtydgjmxuj.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtkqazzcen.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gtwoyzyyiy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthygjhqha.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gtdmvpawqn.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gttiokkukf.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtctottvxt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gthclwuuhm.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gtgzobwvsc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqeihzzd.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtbxxoezds.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gtigrjcimc.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtjdtpjikt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gtdaqsnbki.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyvdpdgx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gtrljhshsr.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gtseisljao.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gtmowuweax.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthemxoklo.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtzsdusmfz.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gtisvkaptd.html

esac
来源：http://dali.nwbrower.top/Article/details/gtjapghpxr.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gttanqjivr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gterjiuisg.html

[R13] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuevlecka.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtxeqskkew.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gtbljdiidb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtkdgwizfy.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtwaewdipq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgehfdpte.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gtevmmpect.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtsemrecnd.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gtczrsukwg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gtmgewvzqo.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gtwxqjggbp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtdfrlubvz.html

[R19] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtoqxmlcdr.html


<!-- 参考信息 -->