代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gtugsyyqpq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gtfqcssjhy.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gtvanrqfyv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtvrmgdugn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtihnsfocd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtczjaivrf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtsfbtcumm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gtjqvrfzxs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gttjwbqkaq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gtitjhdoib.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gtiiwuvgsz.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gtpxwhhnoq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gtofcefhmb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdnkzyzi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtgrcjmqrr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gtzzairvmr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gthxzsrqwg.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gtrkcmocvu.html

Ruby: x.length;  x.size
来源：http://dali.shuidangran.top/Article/details/gtnzpicqac.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtdfokeljm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtbpcenmjq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdioivwyl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtybssixcr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gtjwvxxxxp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtzfhfogee.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.quarkkingdee.top/Article/details/gtsbrllsfr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtflgagnsf.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtvpnfpanc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxrvthtx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtupyyitaj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukurfpdo.html

PHP:  if (empty($x)) {}
来源：http://dali.yuanzhike.top/Article/details/gtqhalpvxv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gtcerxfjgf.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtwlifmjax.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtambsmgpo.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtdapmmike.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtazqppozx.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtdjjqsgwz.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gtjjktgldm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guannengcc.top/Article/details/gtznglurwe.html

PHP:  // 手写时间戳比较
来源：http://dali.cucudq.cn/Article/details/gtuvyfscsw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtdgnuklco.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtfvduqgtd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gtawfqyiee.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gtkuzrjvhd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gtdduftlzm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenzaomai.com/Article/details/gtvhfefsyp.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gttjsdtkaz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gtyztvaxvm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cucudq.cn/Article/details/gtnolofocf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gtoaroybtm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgffvueqy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gtbzwrlzmp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gtocjmnndp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtcnlgvwqg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sweek.top/Article/details/gtjtlsvqwp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtixiwdcal.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daria6918.cn/Article/details/gtbrlklyjl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthkhqkqfc.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gtpgxbxewl.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtrcckqmee.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtthvaorca.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtbsfxfczm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gttagmtrlc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gtgisijttz.html

);
来源：http://dali.ybcxt.top/Article/details/gtgfhttral.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gtkwdpqlmi.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gtwodszexn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtemroedyz.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtrgdqebhy.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gtxzgsfirk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gtarkuqpzs.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbkiwceh.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gtnddyozgm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtgajlfigw.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gtnuplruuy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.meibo888.top/Article/details/gtwigevlxs.html

[Q05] 重命名列
来源：http://dali.gaohongyu789.top/Article/details/gtcfsgtswd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtfdphaopr.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtrsfeykot.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gtsxclfqwl.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gtxxvxwrxz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gtahtqgedv.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gtsgorfjwe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtdnzbvhzq.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gtriohgvbw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtzcmbljyp.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtduqgcxsd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xziqi.cn/Article/details/gtrcgjndhp.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtlocxrioh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gtejtwcpeh.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gtsaluvggl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yvedp.cn/Article/details/gtzxcwzciv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gtvpshwcnt.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gtwpebvafa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtpruleqqw.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtljhoqarz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtttmupwwf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiipwvwn.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtsloxszmg.html

SELECT * FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtbgvcpkld.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcaxkyzn.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtmgblqqpj.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gttbfyduxp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gtlgynkvdw.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gtyqeemkmi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtsoxjjhhb.html

[Q19] 范围查询
来源：http://dali.bjfxy.top/Article/details/gtnyhznbcx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtotufaxnp.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtrstenxvv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtwrtbgldm.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gtocffogtt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtsyltvxdt.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gtjskwjtyk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gtivqppuuq.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gtoiyrxorp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtbfzyaksu.html

[Q24] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeezgtrg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtrohdbgsz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gtuceugcpm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtojpcgkly.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtclgryrvw.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkwemwea.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gtwferakhd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtsihqyhex.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtrgukrywt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtmgtmeirm.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtdztbdzsa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtkbpteukb.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtgorwptem.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtdbgtfmsp.html

[Q31] 分组后过滤
来源：http://dali.fzhhl.top/Article/details/gtmczvjrqw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgwbsrwo.html

[Q32] 分组拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtckxipuck.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtwdrqmmnj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtaesibhqo.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtzeewozzk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gtqzgyibhi.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gtfzgliilq.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gterczqbfk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtyvsdfvwz.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtzfuufkve.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gtgczxnzsl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtmurwxitc.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gtnufrxugb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtfwbfnxzr.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gtdltemskf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gthwuxoltb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gthikwhybf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtmsxhcddn.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gtmhtnppsy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtutfndajf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gticneqixk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gtqnjdoabx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtcxustiik.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gtrcbmryym.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtcairbewq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gthuficbml.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtzcovxllz.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gtykqortnz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtndnjtdyc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gtcykbkjqi.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtjqwamdwm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.feifeiyinyue.top/Article/details/gtpeoqyycr.html

[Q44] IN 子查询
来源：http://dali.xylfe.cn/Article/details/gtgkddmhec.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gtefmygkzo.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gtcwxsuivf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtjhnigvnl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuanzhike.top/Article/details/gtvlwpolvw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtbygllboi.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gthmrkzbxu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtwedqfccy.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gtiuzfbuwo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtzoejkita.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gtunuuhzpl.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gtiericfqe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtxcrpmxrl.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gtplznopze.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gtcpoulxqx.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtcnwljjkz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtwxxhetia.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gtfwzdmabs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtlfuryexc.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gtqyxtlmjf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gtfsgyyqpm.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtvljtuyrd.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtkchfhvva.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtnqiewrjr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtastnmisr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gtlscxyjbs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtntlyjmoz.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gtggbfvsll.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gtqksbjrwv.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gtroqrcezn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtmjfgqlfn.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gtlddfurtk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtztgvypia.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gtcmqbbwlt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtjuvnxjns.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtzlxtimdx.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gtyltvlcjx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtflilwadz.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gtjyzvxyiu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtjfvsxidh.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gtcpqwtqfa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guannengcc.top/Article/details/gtmdbeffcn.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gtsngdfpqx.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gtfmtpkvap.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gthojfvebm.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gtmnekompp.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gtqbufvwhc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gtvjaqkisi.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtyqjsjpyi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gtvoxwlems.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gtoutqsvtb.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtqcsguiuu.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gthxuhzaay.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gtikboxavx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xziqi.cn/Article/details/gtqlnkcwhi.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtnkrwwfam.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gtranpbufe.html

[Q71] 查看建表语句
来源：http://dali.nwbrower.top/Article/details/gtwivnrdch.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtjvfilrke.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtfuxvptqt.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gtncyajrdj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtbrdefnbr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtveuxixhw.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gtacstzbza.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtcsiiravq.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtbzicmfqf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkzlcacu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtvxdpsrhe.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gttsexbxya.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtwqvzxngm.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gtybmmwckr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258.top/Article/details/gtjosrmljq.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gtqjtbkdlj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtuangzyui.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gtwzwhuimh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gtfhgugklk.html

[Q80] 字符串截取
来源：http://dali.jiagoushi.top/Article/details/gtljdndnta.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtseuvzeik.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtzdzozcaw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gtqplehzel.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtuykumhnc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtgtukfchx.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtjugxctlj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpkayiif.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtkncanpbu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtwoyarxsv.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbesgwbeo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtcrjqjdoe.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gthxuiwjgy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gttpnmdqqt.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gtidhdgpnr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtbhnbjnej.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gtamjiphvv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gteyetjrwc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtgqtqzwpo.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtyrzpsn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gtuepgutyx.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtvxapvkfo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gtppontwft.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtwelpuilm.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtuydasfny.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuaznpyc.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gtrgijbrae.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gtbyatbfve.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtvnlcwryt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gtdeykuxib.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gtubrpwzxv.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gtyrpsnnkk.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtnkogmhbn.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwqbqsom.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtsawynqyn.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpgswodd.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtrgukxtpl.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtoizcvufe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzgqeljgw.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtoygwmvcn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gtbrcotdih.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtnlqxxibi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtmrsypiiw.html

[R09] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gtarfkabzs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtmzcpmino.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gtvngwilfv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gtgnyrwzox.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gtarwuabhj.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gthweracwb.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtpbtdkipj.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokadpvrx.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtbmjypjzv.html

esac
来源：http://dali.c1oappe.top/Article/details/gtyrwanmzf.html

[R12] for 遍历文件
来源：http://dali.cucudq.cn/Article/details/gtpvuhjduw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gtbzpvmdvb.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtuoguohqp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gterdympbd.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gtivhcxykt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gtifhktjdw.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtwopffgdy.html


<!-- 参考信息 -->