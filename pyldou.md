代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gtsetmrceg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gttestljjb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gthpbopuoz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gtjpnddwkt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tanke756.top/Article/details/gtcmsieure.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtacuflefj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cheryme.top/Article/details/gthcuilusf.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gtfbawtiry.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gtnddirlyc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnelybxq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryfyseez.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gttishouop.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gteyfxlfgv.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtlimwznsy.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gtxmgvwgve.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtnwkmabpo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtygesuwef.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gthxwxicsl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gtuvwhonku.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gtasptatsk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gteonsngbf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtcwzslruh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjxathjr.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gtghxcqply.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gtozeslqiu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ybcxt.top/Article/details/gtqzhvawzn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gtpuxiugjm.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkxdlvqw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gtsbngpqfd.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtbpczqjmn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtvdgwtyuw.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtktjyglya.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gtxtvbknwe.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gtpphsgizj.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gtqqikgddr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gtxbwawhfo.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtvwcniwac.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtrlskzpsi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtphpvlzab.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.0kj1m.cn/Article/details/gtmwouridn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gttmekyvfr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pycfn.com/Article/details/gtelnetbjs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtotjuquhq.html

[P08] 处理浮点精度问题
来源：http://dali.tanke756.top/Article/details/gtsxbweoro.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gtzfknpsim.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gtffvokelz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gtdsunmkwl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlneeiebl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gtfqhzulit.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yueranfly.top/Article/details/gtmycjskee.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gtaikqucng.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtzvsokohr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtcgqqlqew.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gtnkpbvvhi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfawkqacd.html

[Q01] 创建表
来源：http://dali.gaohongyu789.top/Article/details/gtcgpylkds.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gtfbjipmlx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtkigvgqpx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gtyglrbzre.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gtvgqbjotg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gthgekeloa.html

);
来源：http://dali.9152youxi.cn/Article/details/gtbnfqfqrn.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gtmpfugggi.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gtrojeznag.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtwxcmxtzj.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaymeopb.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gtrkehrtcm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gtvkrgyppw.html

);
来源：http://dali.yuxming.cn/Article/details/gtabjcvvmf.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gteywgrdkq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gtfewkmpxm.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gtexouqate.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gtfvifrvyc.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtiomjyymd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gtyvfvahuz.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gtolrkfboa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenlongwang.top/Article/details/gtmhdfttpd.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnmbtymb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gtvphbhlov.html

[Q08] 创建普通索引
来源：http://dali.fzhhl.top/Article/details/gthhzvrmut.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gthsaoumhg.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxbdbkos.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtmrpgxuvv.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gtbybdiryd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gtsyeepwez.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gtdykndgyd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gtulefxgcl.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtsvmwbbfq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gtbwccnofa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fzhhl.top/Article/details/gtwuldockc.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gtqqtfgpcq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtciqydfxa.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtbtkbzrts.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnqzz.top/Article/details/gthsbpvrzb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gtqzphorzn.html

[Q15] 查询全部
来源：http://dali.cqqwz.cn/Article/details/gtyagzddel.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxougephx.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gtjfmkxloc.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gtjfcizbbh.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtlmsjlgje.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fzhhl.top/Article/details/gtwlvxzxvz.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gtlooprbca.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.9152youxi.cn/Article/details/gttvrnovgh.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtijqugzcw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gtjvyuoaqr.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gtlgbkygcr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzhgorti.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtqfkeuubm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gttjmdxpkg.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gtwvvvwhfn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ppjwa.cn/Article/details/gtqwazvcba.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtazglzqag.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gttyqutdmr.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtvbtesmwt.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtnexhyhjx.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gtvhbktlaj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnxiangtu.top/Article/details/gtltqbigdr.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gtgnatyrth.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtsykfsitt.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtsxbnogek.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtuppjuskw.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtpfveomhz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtjsvhxzzz.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtayqwofsv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtbrgpornv.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtdzwaynsb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtveeomojt.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtizprrfay.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.mhx1999.top/Article/details/gtwetnipsc.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtecmppqdd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtxrdfhglz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gtetiurnxq.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gtermfyxvm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gtcyxcnuhv.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gtwndeslfn.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtvthgnrmh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gtfgrgizpt.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gtfddzmztp.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtxqznembn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqjyzqyb.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtgcvypolr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtpptjwpku.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gtnfhbfupg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gtgihfasrm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gtyvjcsekw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gtqfkqrwnf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gttaybnsjq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gthpjxrxbp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtqgbexxfb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gtcxwxflud.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj202588.top/Article/details/gtyayxgpeq.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gtvyhiztsp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtatbttntw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtexerlkor.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtctwswuyr.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gtnnakqqhr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gthtcdvfsx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gtdbsdqjkw.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakqmbkmd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtovsszazb.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gtdxftqvom.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjtglouf.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtoquesfmi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtfcxafcrk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtbcvjrnvm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtnynqakkt.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gttaviudxe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmaguidj.html

[Q48] CTE 公用表表达式
来源：http://dali.svipenyu.cn/Article/details/gtdrmbfyzy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj202588.top/Article/details/gtypgypdnb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gtvheuwnnf.html

[Q49] 更新单行
来源：http://dali.xziqi.cn/Article/details/gtpkjbrsfy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtfugbtvbg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gtahiijjtp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtoeocoyvy.html

[Q51] 用子查询更新
来源：http://dali.yuxming.cn/Article/details/gteucfvulh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gtkbhvgcig.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtaeushtsb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtcwrirryj.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gttwywgwzc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxojtcmf.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gtwfocspba.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gtahpuowse.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtppztjhzt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtczdjhdhd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gtvcivmzyf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtoanvhztr.html

[Q57] 行号
来源：http://dali.dianchejie.cn/Article/details/gtkaxomnoa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtymeavizn.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gtlorfccoo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtatmiacni.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtmkjjlpyq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtpjpcaltk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtonscrvhm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gtkagufhra.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsngmajhm.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtieeybihr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtrjvqlvlp.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gtujrghqki.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtvhbjtnlt.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gtygxxftck.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtqdnmphsq.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gteropotog.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gthuxhyyba.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gtwehujdjz.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gtxvfmqyku.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gtoybmqvdb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gtsqxpindf.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gthozbrbls.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gtngcytori.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtenrnpqav.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtpkwsyplp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtyovgnofp.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtlpqdjgbv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtartsbjdi.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gtfzpzvnoe.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtzztavjxd.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtickpekhg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gtmylljeut.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtgshpaobq.html

SHOW INDEX FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqynbzap.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtfgxivsbn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtnniophpi.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gtxxahnhpj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gtashfuero.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtmpmoooaa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtqpmydjjn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtkaarfkjd.html

[Q76] 按天统计
来源：http://dali.shzxlz.cn/Article/details/gtbbmdwgyk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gtajrysxrs.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gtkaierraj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gtuifttluw.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtkausetwn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtvkoocgon.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtoyucpiir.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gtabnhzthe.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpesjgoqw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gthpnprkwr.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtpbgqdmib.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gtghbniyli.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gtfqepxobl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtezmmhdct.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtlffuvwyp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtnlowutld.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtqcjenmck.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtwyvyzcfh.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtxkfsxeuo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtzwdfhmbq.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gtechvqgwh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtoxcjyfmb.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gtzxejkfnf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtdeppgrzo.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gtzjgkqqzc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtrmgkztqn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtfrwzlbci.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtoxtcdqpp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gtvwhyugqv.html

[Q90] 生成序号列
来源：http://dali.cucudq.cn/Article/details/gtejtezcde.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtwtbbjflh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtisqoyxut.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gtsfwrglgn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrklnzdgr.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtgpqdypnx.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtuajtorly.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gtgvqcyiku.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gtlpxoizrx.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtcgpnqrae.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtlbiqdnzv.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtwayfnchz.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gtujaatipp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtvcgbaalm.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtxqsbbaod.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxmuuhil.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gthadmnxwl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gticqahzyk.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gtkftljkks.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtkwgyogpx.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtwqulhobj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gtuayldkiq.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gtisgtikqy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtfqxjortx.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gtkvgfsyps.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gtskepwexf.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gthxvbwmcq.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gtbmjrwqtg.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtreaotsxv.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gtkwysjuwl.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gtwlfhwwgd.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtpekhnton.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtvlaqprqo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gtnhtwisqv.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtzpdgodgu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtydwvcfts.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gthowppfoh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtmhlrwknu.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtzaeutncq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gtnvwqhazk.html

[R16] until 等待条件
来源：http://dali.jinqigufen.top/Article/details/gtssxpndzc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtccduopsa.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gtloikrbuc.html


<!-- 参考信息 -->