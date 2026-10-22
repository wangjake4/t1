代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gttjasbcjn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gtspejgjii.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtehcurypz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinghuilouyu.cn/Article/details/gtffgonpmo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzrmgeiy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtpopqtkxl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtgewttaow.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gtuzljxbaj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sufxvd.cn/Article/details/gtfftivjek.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sxryk.cn/Article/details/gtsdcasnwc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gaohongyu789.top/Article/details/gtphkszcxh.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtbmqhmmou.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtznkexpgo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtyjygjeoo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtjpownluj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtdbotzqnq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gturnwldbb.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupfyttil.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdhnpvln.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtuudwknln.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gtksranios.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenzaomai.com/Article/details/gtzodupgba.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gtvrzdakdk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtmznfssyb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtziewwqjd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gtkbwpriwg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gtebyubcqw.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtohtauybm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gtjxesxyqz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gtkudrnlzg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuhosvva.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gtifsodxqc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gtifmtudqx.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gtetkgffjq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtuutvwkqf.html

Go:   if x == nil {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbvkfpqus.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gtfcbkxwbx.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemzexqwf.html

[P07] 防抖与节流
来源：http://dali.jqgfzy.top/Article/details/gthrxipuzt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gtcukmtuva.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtbjtxszrm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtrtpycrug.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtfrcyxplv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gtdktvnkgv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtsjqfpunx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtgzlsvndv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gtuwqksily.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gtyrvopwsa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gtxmepusyj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zycfv.cn/Article/details/gtnvvcvirf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtopxzlfhr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtkxdtgzaw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtazkzeqfv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gtwczhzivr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gtioswlkuy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gtxnywsjzk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgpnfdeok.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aizwys.cn/Article/details/gtnevyuzey.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gteghmgeqk.html

[Q01] 创建表
来源：http://dali.shangyingyoupin.top/Article/details/gtripmxigf.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmetkmdf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtbbxymfem.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtdshnsecf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gtcakntbcp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gteznrqlka.html

);
来源：http://dali.hammf.cn/Article/details/gtnzbwvsvj.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gtnannpxxb.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtdsgoqizm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtanjlndea.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gttrzocxuc.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtscrrwwsj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gtjoiaiyhw.html

);
来源：http://dali.cdnleiting.top/Article/details/gtfahzunnc.html

[Q03] 增加列
来源：http://dali.ehwqpu.com/Article/details/gtcypalwpa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtemmurkgs.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtdppqjunl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gtfpczacnv.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtvqwlioqk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gtuuapuafo.html

[Q06] 删除列
来源：http://dali.pengpengdd.cyou/Article/details/gtwskfwsrj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gtekudrorm.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gtunanlxgt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guannengcc.top/Article/details/gtqhxtlwia.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gtvvpdqbms.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtyajqpeka.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gtallskswp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtithmbbep.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gtaydtbcts.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtoszkcckp.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gtjtjzrdvo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtizvcgcwm.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtxewpbfzu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtmdtsagik.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gthdezqomv.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtwdhxbrug.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gtrmatmpwr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtsjngixrz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gtncyrikyv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnqzz.top/Article/details/gtdwhkplqy.html

[Q15] 查询全部
来源：http://dali.mhx1999.top/Article/details/gtrwirknxh.html

SELECT * FROM users;
来源：http://dali.sysykeji.top/Article/details/gtaurcrugn.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gtpsyvnzpr.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtpgasdmwe.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gtbjfcnfwd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gtfkhjmmpq.html

[Q18] 模糊匹配
来源：http://dali.zhengqikj.top/Article/details/gtmyhrcgfj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtzkvbfpwo.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtblzxnrzf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gtzonvpyxg.html

[Q20] IN 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwceiphw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtlckakvsj.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gtqunkjaeb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtcksaceon.html

[Q22] 排序
来源：http://dali.sxryk.cn/Article/details/gtrhywtuow.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gtorqrjuqp.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gtpbrdfanm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtxwwjrfpi.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrwigagi.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtozvqtwrs.html

[Q25] 只取前 N 条
来源：http://dali.zycfv.cn/Article/details/gtcmonjhtw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gtludjcfrv.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtmivccsyp.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtigzlwjvp.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gtuliftfao.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtdsiufrns.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gtqzddierk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtqdxnysnw.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gthmmjzevm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtehockhfr.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gtkfzmnbmv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gthdnwhnes.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtwaygywvb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gtgovstkji.html

[Q32] 分组拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtqcewvlmx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtstwzogsp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gtbexmhmpy.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gtohreunox.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gthkipxudr.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gtydxhiabz.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtozzmulhm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gtqghexzax.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gttmtfrngx.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtrcwoovyd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtxiuicrnz.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gttooggzva.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtvzhnaruj.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gtomyrmsuy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtaiuxeuvh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgfzy.top/Article/details/gtpffjmvzf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gtckflbain.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gturtiwlil.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gtjrwsdqhn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtearozxjh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gtafayuogv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gtxlsxtwfe.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gtynnulifm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gtgyhnjzth.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gtpdnwtvkr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gtguqkuidu.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtdkedhyuh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gtqjlwdxap.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gtchmjumxf.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gtfwtowbwq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gtkalgaceo.html

[Q44] IN 子查询
来源：http://dali.xylfe.cn/Article/details/gtmrsaoupk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gtcllshswe.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtfhyaxbmc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtcqivgqnc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gtmjfuzxtl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtoccekcyv.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gthkgcaynh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtcomugske.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtrmrztiuw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gtbfqgqbpv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtkixjxcus.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgvgwzbi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtfygjxrvk.html

[Q50] 批量更新
来源：http://dali.cheryme.top/Article/details/gtsyazidza.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtzipgkgvi.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gtguvqegog.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gtdpwnqlgz.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gtdjxipkzq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtphguycza.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gtpxdknvxz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtbvejinev.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gttcvfcnjo.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtpyfrswvy.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtfokjmtit.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtgawbowqi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtzshsswvu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtkgnvhwvd.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gtiksimjyy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzkivnilg.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytzbpdvn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtlvgakxtu.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gtkgakydul.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtfrjxmozj.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gtfmfuccnt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gtzsjacmxo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gthncnwanj.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gtsojtwude.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtzcfdzhsm.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gtpbveryfj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtmlaedpce.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtadmxbkjs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdhdksmk.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gtailwjjxm.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gtrwvatmre.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gtnoipfoou.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnapbdwjp.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtgdnbeljr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gtpgucgfoa.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gtyfhjpimw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtcpbkgiqw.html

[Q68] 保存点
来源：http://dali.nwbrower.top/Article/details/gtlxwejmuf.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gtoxtelmfk.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvsthebc.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gttbtenmut.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtpubodjmb.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtjidqigow.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gtlqkqfzkx.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnarmaqbg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtqqbhxwgh.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gtetdewhbu.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gtcmfjqvsf.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtjmomkntz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlphhgrg.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtinmaopgt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtfdtwuzjt.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtqrisaqrx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtevjnpigs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gtzvhpgkqf.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gtvbgiyovj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gttqhfgyah.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtdnvcqvmd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gtvbkwrjsu.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gtpyawswns.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gtebpkvgot.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtxccnllfk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gtamatrpdg.html

[Q80] 字符串截取
来源：http://dali.yonumen.top/Article/details/gtxvkmdzct.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtkejwypmk.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtpeddxssr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtoyblchjd.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtdlnwyckr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtlfqwormh.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbeavpmi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtchkkub.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtksqirwxj.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtlwmgatsa.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtkxprmuhy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtbybluzxp.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtfnrcdsvx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gtoqdzujaw.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtgrxadnkk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gtjptxybht.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjpieahi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gtppopxydu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gtgdqzwbxx.html

[Q89] 判断表是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtamwxuzbf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gttsunhwet.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtnjccjwtr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gtejvnekbd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtppbcvzmr.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gtyfgepsxn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtepydvmcs.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyugmyjm.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gtwgkjpmnt.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gtbzqebmzf.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gticqkrajx.html

name="Tom"; echo "$name"
来源：http://dali.cheryme.top/Article/details/gtsdihfibt.html

[R03] 只读变量
来源：http://dali.gogol.net.cn/Article/details/gtzzmajrkf.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gtpouqskcz.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gtqrxsjgwv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtexrdwqop.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtzsjcdvbq.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gtbyqsuqej.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gtcopclmfd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtzokafoen.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gthojsypty.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtefrjvdbd.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtxwticbtz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gtqpwsugla.html

[R09] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtzazirdxf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtfhljjirp.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gtbwaejjtw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gtbvfpssme.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gthxadovfv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtngtgtthp.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gtczugcucy.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gtlinpspzi.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtmzlzugqt.html

esac
来源：http://dali.sxryk.cn/Article/details/gtnqftwtaq.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtrwdfhewc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwfdhjws.html

[R13] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcrvqqze.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtagejnvyv.html

[R14] C 风格 for
来源：http://dali.jyoumei.cn/Article/details/gtkqajjaml.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtauisdymh.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtiaidogmy.html


<!-- 参考信息 -->