代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtownrvbai.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gtexhokkna.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtvzsfxvma.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gtqlnaqxdd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtpjdpsyen.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtbsxzblfw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gtpuvbninu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gthhzukzwa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtgrtdyhya.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtvxxtaehv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gtogrgkruv.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtnwlsiowi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtjbimikbr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoqnhset.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtombuyjdp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtvozispbl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gthoekihuy.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gtibguotkg.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gttmmvbpaj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gttlbhfucv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gtphkupzwm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gtfddzulmf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtfdcsivoi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gtnaxsnfga.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtetydbahz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gtfkjktdgy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gtehccnuye.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gtcghckxop.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gtvmbuaziu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenjidiqi.icu/Article/details/gtihxvuyix.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gtggwqcgrb.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtjukvoifp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fengsongda.top/Article/details/gtdgelfglf.html

TS:   if (x == null) {}
来源：http://dali.tian-w.cn/Article/details/gtrofkpsad.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtmjezlenp.html

Go:   if x == nil {}
来源：http://dali.meibo888.top/Article/details/gtafkvxwfe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gtmqvmmfqt.html

C#:   if (x is null) {}
来源：http://dali.316326.xyz/Article/details/gtlopyguqq.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtytxihfmj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gtmkbuulgg.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtqbnilarm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtwsyfmech.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtkejdbfis.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gtjucdkilw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tanke756.top/Article/details/gtzvhjdirn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gtqqxwnjww.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gttslktoyo.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gtvgzkhndw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtxunfmuop.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtvuaztcve.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gtryohojpq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtssooryow.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gtydwkytug.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqyrhtha.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gtgoctswdb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gtufdsrbmb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvotgkduc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daria6918.cn/Article/details/gtvakynaug.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmmmxzmdo.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtrofzamcv.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtunpoqkvt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtacfwpaei.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtfurtwlix.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxpyikqd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gttzucxtma.html

);
来源：http://dali.bjfxy.top/Article/details/gtoczclros.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gtmvjwzqea.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gteshqjwqq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtkqyukmch.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtjeqieeet.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlhihgnm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtxctqygec.html

);
来源：http://dali.jyoumei.cn/Article/details/gthdfduizz.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gtakskkfgk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gtirltksch.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtckidfhfr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gtpuqbxofx.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gtfhuabvsp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjenpfdud.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gtiedwiggl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtykdztpyt.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gtcjszniau.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtkdsjmkyb.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gtxegjazfh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtmnynulqj.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gtfpkhydxh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gteemlgrbe.html

[Q10] 插入单行
来源：http://dali.zhixingplan.top/Article/details/gtqwyfbdcz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gtcddikzhg.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gtlpkcmpjy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtmoapvlpg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gtthdudwyo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuufbyzlw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtqdmkuvap.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gtxmuqnpmj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtfpwkrxee.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtwkuqmgcb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gteaxpxsam.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gtzkcnnphj.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikgecysz.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gthpoyaest.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtetbhhsad.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtozcxistp.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gtfvcrgtdx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gtcyrvywrh.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtepmgilul.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gticgxikcq.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtuxqktdzm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aibaodan.cn/Article/details/gtlfxdjehk.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtdiqibeif.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gtgbgbvqwv.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gthpgbexwy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gtpykucfup.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gtwuxrmysq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtpdqetcbz.html

[Q23] 分页
来源：http://dali.yongpay.top/Article/details/gttehgwpdp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gtksjiddof.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gtgfdqxqot.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtutuplfdh.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtvwwsospp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gtqstzeumg.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gtqlqwjdko.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtglyjdsvd.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtfwfbbvai.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gtxybefkep.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyovpqzpy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtalxcnldd.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gtwhphnxjd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtvtfykcen.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtsbkkyjty.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtvioswqmn.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gtornyaonw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtzzaalphm.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtnaivttss.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtiivrajyr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cdnleiting.top/Article/details/gteielwnpc.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gtfqwscnao.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gtxxafsvzh.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtveupixod.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtfzwvsqjt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gtjcolqvov.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtuaefkvnm.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gtotyolabf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtfntzbvfs.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gthxwozuff.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtnwduoisg.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtxvvprdop.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gttlkfctsg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtnmytxphk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtxanbxfld.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gtjflhertd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gtinjkbxex.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtzjvkuuqj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gtahowfbkq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gthrjggpet.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gthvywdrju.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gtdlhnzdsx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajodtkmd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gtuojwrmwd.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtfdeykeoa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtrdtvedbh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtpuyiezij.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtiszicxck.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtxidzgfyp.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gtzmmguqrm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gttsfpwltj.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gtocdappvu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtynnqruzd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtuppliguf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gttaswdoja.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gtkjqpyzom.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gthdnwbjkl.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gturywrbft.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gtizsamhkb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtqsxsttkj.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gtfvabosty.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtbsgtnoln.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gtwfhjmodo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtmjbactqa.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gthfcjgwwo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gtkzbyftgv.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprojvlcd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gttfsxogrq.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gtkfvuvtzc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtkzfeixhf.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gtifflcehm.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gtbfyibhtl.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtofjbxpte.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtrmunzobw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gtrrhzqnqm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtzinpcnco.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtsdfrvhdv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtxdzphkgh.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtsxouyzme.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtgccllqyx.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtznredbuk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtbvgrhrmz.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gtwwjdvrrb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtipzihmqv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtlsiogiwi.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gtbfamxpsa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtlmyjcivo.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gtcpegrsgw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtqefjduzt.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gtbrwmzkgs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gtlzllvrqq.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtkrwldloq.html

COMMIT;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzslxtqz.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gtbfzrhpfx.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gtbaxsifeg.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqokormu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gtxfvbuqqd.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtvlqsivpl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gtrghizivw.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gtkjlxbkgz.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtckwwnnlc.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtcipfabym.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtwotvhebt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gtydvmvzkx.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gtdwgmllfk.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtwofvufhl.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gtwkkdgrba.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangshuangyany.cn/Article/details/gtdfrhmwib.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtmntakyze.html

SHOW INDEX FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtyecisjtd.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtaocrkbwi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gtfsfftkaa.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gtvvccbirq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gtcvqwqlhw.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gthhvfgxqh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtakzkodao.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gtiohkqljj.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gtenlyxmko.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtfvujbbjs.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtdkaqmzjn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gtbkmpziqi.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguclxeif.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtscfumxzh.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtsswenozr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gtvlofuriy.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtksasetlb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtpuulzxau.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtymvummoo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtpchafeos.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gtbxbdstcd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtgukygdhr.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmungvtxx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtzmfngxbt.html

[Q84] 去除首尾空格
来源：http://dali.c1oappe.top/Article/details/gtwwthfddw.html

SELECT TRIM(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtanrxdzds.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gtigmsddey.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtrwatmxcl.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gtrnegdrei.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guannengcc.top/Article/details/gtkpkqlikg.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtddggpdzj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gtzyyjyigw.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gtsjjntovs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yanxiufei.cn/Article/details/gtssdabdrs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtbhitfpho.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtvehskczw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gthgecckgp.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gtckdihwme.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtpyjigwek.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdasaqbxg.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtbqhrtnpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtegyuzfmw.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtfojdrybx.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtvrxcfglq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gtuqtcgfpd.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gtitrbzdii.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtyiplftyi.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gtxluvxaqa.html

readonly PI=3.14
来源：http://dali.xinyue.icu/Article/details/gtrqysdnmg.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gttgtotzxs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gteltjlxli.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gtvdnncqzk.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtokykvhyo.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gtdghrqmjm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtsggnmrda.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gthnzhyrqj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gtzrsnuduj.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtvlorldyp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gtfnogvhnb.html

[R09] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gthkcixwtu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gtybmazrck.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gttkpznzpv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gtaqzmafax.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gtnnexiizh.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gtpqxfzxnk.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtqvdewojc.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyrsmxsb.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtpgjahgon.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gtuyvoluqu.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtwhwughjz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtylspdujv.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtbyocqunl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtirzovpnl.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtaktpytkm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gthbxazhux.html

[R15] while 逐行读文件
来源：http://dali.pycfn.com/Article/details/gtzwpikqzz.html


<!-- 参考信息 -->