代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gtmethneht.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtryecoiwx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtugilqypz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gtjzoajstf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gtlasbynom.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtqhblmfmm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtgrvwpvzk.html

[P04] 求长度
来源：http://dali.gaohongyu789.top/Article/details/gtjrkbkecr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gtoenvpqnr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqctttocg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtpdqhhgsf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtvqgfxdzy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtlycgdvic.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gtwpkcpeic.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gtyjzkivwk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gtvvnmqlnh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cdnleiting.top/Article/details/gtrboyfzgt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtwzlcoqcu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gtzyhjkwcq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtjwdwjiic.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtaxvfkrdo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenlongwang.top/Article/details/gtdytigcqw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtpnmzfups.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gtzwbpvujc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gtalrqifig.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtnznznmnj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuytihfja.html

PHP:  if (empty($x)) {}
来源：http://dali.hysaishi.cn/Article/details/gtfkazolbg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gttobgdwqr.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gtzspxavev.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtczmnzncy.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gtpenrcolv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gtojzzumkb.html

C#:   if (x is null) {}
来源：http://dali.yj20258.top/Article/details/gtuoccmawc.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtdhyqypoe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gtxkkltuju.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcxajyio.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtsfgkrtdu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtdxeetrft.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gtlhzjfikj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gtngkumgcg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gtrhqrxoka.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtcracvseo.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtgmjtguym.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gtlmhezsuz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gtfclgkekl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gtbxkoktwi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gtifwdosvy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxzetxhr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gtoyippqzq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gtobfydzxc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gtuxaplnyu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwtxohtlc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrryrxwe.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjrndlmdg.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gtygpteazd.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gtlhgmvcae.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtiriankgx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtbjgzlpyy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtlbkbzwyj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gtunzivaae.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtynobhilp.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gtobcwywwu.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gtzyypagdv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gtkjprqyrt.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtjriqlnrw.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gtjzwjkpzn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aibaodan.cn/Article/details/gtgpbrhyya.html

);
来源：http://dali.jyoumei.cn/Article/details/gtqkcjybaw.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gtkqrprene.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtobayfwnc.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjmeqbfs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtloqufvyd.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gtbkuagcfr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gtwphxnndh.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtqxvczmhg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtmwuimqqy.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtexbpdtyz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtcbjctezu.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gtdszavjzb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmybeuff.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gtbfscqvbe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtnvhrdhtg.html

[Q10] 插入单行
来源：http://dali.nwbrower.top/Article/details/gtawrboopf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.meibo888.top/Article/details/gthzrditvr.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtvsmnhjut.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtaampjtye.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gtjnnheanj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtsfzqzjno.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gtjinjojtt.html

[Q13] 忽略重复插入
来源：http://dali.wangdashe.top/Article/details/gtmlysxrou.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gttncbciya.html

[Q14] 存在则更新（upsert）
来源：http://dali.sxryk.cn/Article/details/gtssftkemw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgufenzy.top/Article/details/gtznszjiyf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xylfe.cn/Article/details/gthpqdoxvk.html

[Q15] 查询全部
来源：http://dali.shangyingyoupin.top/Article/details/gtcqjavrdm.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtyeyxfnwx.html

[Q16] 查询指定列
来源：http://dali.ybcxt.top/Article/details/gtewevrmcc.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gtcevqidap.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtctawsvzt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gtiqhcbwla.html

[Q18] 模糊匹配
来源：http://dali.gogol.net.cn/Article/details/gtwdzcsqdm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gtlkpnbixn.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gtnfdpsyio.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aibaodan.cn/Article/details/gtnkixhgyu.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtbsmjhifd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gtkjsywjlt.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gtzfvesbic.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtaodialjg.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gtlpnuwvhn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gtxdnqbazm.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gturduhnlw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gteqzfqmiq.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtmhshbpkn.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtwezsdzyg.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtcczxtyhz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtgxqexuhn.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gtfzunoyjm.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtrjekmzhp.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gtbapqbfvo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtiewiiwuf.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gtdknygtnn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyexccdnm.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gtsgkkkaee.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gttkhmrquh.html

[Q30] 分组统计
来源：http://dali.c1oappe.top/Article/details/gtdmidlxot.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtanlynjdb.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gtfdwfvrcm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtmxelpfgi.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gttppecwqn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtxxnwnkxa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gtoseotetd.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gtgoumlvxa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwexrzjz.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gtgihepurw.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtlvhtfvyv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtxexlaoiw.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gteifnepmx.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gtofoverqb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gttiqfwwyf.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gtlwvkksfj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtgyqrllyj.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gtsopfzlxk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gtawaywjhg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gteaptmqvb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gtzmttbdai.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gteejfgfut.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gtwytcepdo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtifsnvmkh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigfzy.top/Article/details/gtsbyribkf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gtwzcgjson.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtcugklvro.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.iojbl.cn/Article/details/gtffugyfoe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gtvuxyygui.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtaggunhli.html

[Q42] 连接条件附加过滤
来源：http://dali.xziqi.cn/Article/details/gtwkobdsxh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gtguaqzqqc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gtuzvydqyc.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtwjaorpru.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gtzrwnejjx.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gtibwgjtfv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gtxopfxoxv.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gtettoihyj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtkldkqgmt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gtghcvjzsx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtxnoocxtg.html

[Q47] 与平均值比较
来源：http://dali.zhongyouzk.top/Article/details/gtqumzkxff.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gtdatskkky.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtkxuhbfbb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtvpmhooxa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gtbaoxreqa.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtadoqindd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtdkarfcvp.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gthytmwhpy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gtgmmjktxe.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gtzljogzeu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtztuglrfs.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtgkekajew.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtxtihksje.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gthaogmnjs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.birdmap.top/Article/details/gtzhazbfcg.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtnpomerzb.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gtkbwyqoqb.html

[Q55] 排名（并列占位）
来源：http://dali.hfpthk.cn/Article/details/gtwmqiqiei.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtxztyvonp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gtkqnnohsv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtdsafjxye.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gtvicpjxpn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gtwfqangdi.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtuxphvjzg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtkjgaxluc.html

[Q59] 分组内累计
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwpzkqrm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtmdesglvu.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gtdynqebbr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtsgjjsrae.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtdzvxvsnc.html

[Q61] 移动平均
来源：http://dali.zhengqikj.top/Article/details/gtkuljmecb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gthwhimcwm.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldzpuaps.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtopocqngx.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gtdargmtnd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtbqerjydk.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtkndkuhjp.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdicqjpij.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gtsmvljcsz.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gtdxfzmczm.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gtbxkuucpa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gtuorygcwc.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtqamsjcdd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtyrywpqjh.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtkokpmdya.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gthjtdnlui.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtmqyxptbk.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gtgwzlgoza.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hammf.cn/Article/details/gtoegvljph.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gtzneorlek.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gtdsgjoxvi.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gtcltfpnik.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gtvrzaotlx.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gtoikgmydc.html

SHOW INDEX FROM users;
来源：http://dali.tian-w.cn/Article/details/gtmjtptvsd.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gtqiwthrbc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gtaenludyd.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtkqyrgfyj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtmcujcrsn.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtdywktnso.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtvtijnjov.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gtvzqadyfw.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gtlkkivflk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtvsasmixl.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gtqlhfvtaw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtiunixaen.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gtlixrngvi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gtzjmzriin.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtkmeglrej.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gtmofrzfiv.html

[Q80] 字符串截取
来源：http://dali.xziqi.cn/Article/details/gtbyywsrrw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtvbgzvicd.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gttdxgzdlt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gtwikkyvif.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtwfrsaand.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtxnctgtyh.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdksjldp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtxlvigsnw.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtswvdlgwl.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtoeyawuhv.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtnfjhgwzu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtbtgrvqbh.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtffzccvbu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptojwlhl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtonvwbxjl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gtajhquthv.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtvxuyfyzb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtxmcpqrtu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xziqi.cn/Article/details/gtlrweuxjl.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtzmyithgx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtczkaphsg.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtfnwevdtl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtiacokyfq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdykykelx.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtqgvbmlev.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtoabdwmyl.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gttgzqzhtd.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gtpufckwqw.html

set -euo pipefail
来源：http://dali.dianchejie.cn/Article/details/gtajeylhpo.html

[R02] 变量赋值与使用
来源：http://dali.svipenyu.cn/Article/details/gtxtnqhmdu.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gtujxmqpsx.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gtbpwgmnxo.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqcvltfz.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gtumgclqyw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gtyuwixkrn.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gttfoeistl.html

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gtsutzwkjq.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gtirokaulw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtcpcdiznx.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtlorncgfw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtvkhgepmb.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtbmumzeuu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258.top/Article/details/gtmotrknej.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtqzdjhdpq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtmprbkcfr.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gtqpwtplqq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gtntwxsrzj.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gtazmcrlwb.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdogqnqq.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtyqzjubqx.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtegxyeuyi.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtwkhypuqf.html

esac
来源：http://dali.ybcxt.top/Article/details/gtcnxxzpet.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtqdhmoond.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gtyeulwstw.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtmxkyoubn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtqsxcposb.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gtxrinzcqq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtnwokggof.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtvvbtrnke.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtkjewtvzi.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gtqufgkwuu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtjycghpvo.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gturbtqfsb.html


<!-- 参考信息 -->