代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtmxiylxsl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gtndpnhoqc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gtkhdyilwv.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgreiypui.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldlpayfz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtbzaccwva.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtcvmlmfsi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgneafttr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gtgpmogiye.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtvpizuelm.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtecaztvxq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtctxcmmge.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cheryme.top/Article/details/gtmaohuqas.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.havefunace.top/Article/details/gtbjzqjczj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gtllojioah.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtuuooegam.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtmtlxlmqu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorbsujzv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtgysqaick.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gtaevsvbwo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gtqbzhonvy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daxiang520.top/Article/details/gtekwksgfe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gtfbrnjocn.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttolsfipe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gtudkuwaob.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrczfbbfz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gtssiccmzd.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtifvtapbs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dianchejie.cn/Article/details/gtfetwdnld.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtteolwsow.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gtvvluorjy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gtmjywkzhk.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gtwexxeptn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtkxnbfstc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtgwaytife.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtuhfggtpz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gttjjznbox.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtxmbtkdon.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtupegfyij.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gtwglozdxl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtjooopfrs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtitqtokrk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gtbdyckukg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtiaejupne.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gtryvvuzls.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtshanzksc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gtimfwwkft.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gtdfwgzapr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtehfuxuie.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtyzsyemgy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthqwzovez.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtxexaxokp.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gtkenbynqg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtxfxkilne.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtbgrmhuvd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtcolgotll.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtttodftio.html

);
来源：http://dali.hywenlv.cn/Article/details/gtzudyrhsc.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gtjzgqtxcd.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gtrrcalmyy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtazsoeiww.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gttmmkepua.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gtshxaqbfz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sufxvd.cn/Article/details/gtrmbohetu.html

);
来源：http://dali.yuxming.cn/Article/details/gtdtgigrdk.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gtyyhmqdvo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gtzvktjcqz.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gtcsimbpet.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gtjjpfbzgb.html

[Q05] 重命名列
来源：http://dali.jianghu66.top/Article/details/gtvfsralsm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtympnugrd.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdfepwxq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gtpkzqxipj.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gtmfxpsebj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gtvwvjrcpl.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gthnhwwalx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtocuyqnil.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtqaaoarfl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtifathzbb.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gtsdyezufx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gthfbsetuf.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gtiqgzjuor.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jianghu66.top/Article/details/gtlhrjxzlj.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gttmaqbahy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gtxqorrncw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gtuouvisab.html

[Q13] 忽略重复插入
来源：http://dali.wangshuangyany.cn/Article/details/gtbkwsrpys.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtgumozksv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtkbxvijrj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtxpcktqmq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gtgbhcruqv.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gtjyegzhis.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtyiwknlwv.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gtdbikmtlk.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtdnifhqiu.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtykxspnfp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtvbwyurkj.html

[Q18] 模糊匹配
来源：http://dali.vqdsnc.cn/Article/details/gtrjrekspe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cashguo.top/Article/details/gtnlubqrhj.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtrstcldlb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtuhassufz.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gtrbzrwtnb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gtdnynymkl.html

[Q21] 空值判断
来源：http://dali.xinyue.icu/Article/details/gtidwfhbdx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dashuyun.cn/Article/details/gtejxxgxin.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gtrfqtaewe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtawbabmux.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gtdccyuril.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtgknzskny.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtmpzisjyi.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtkpyeeisj.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gterqnjcwu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtkhswhevg.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gtlfxbpsqa.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtedbvpydg.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gthwvojwqy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtcpdylapc.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtdwzyikew.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtzlfmoxvs.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtqfrkrxfm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtnwywxxlu.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtaswjcvau.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtgtozxnvk.html

[Q31] 分组后过滤
来源：http://dali.sufxvd.cn/Article/details/gtgpnbzggj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gterwsunqe.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuoupkee.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtvurxhqqw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gtpghgyqqo.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gtqbyoflum.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gtuhznkhrp.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gtmiuyjfuk.html

SELECT * FROM (
来源：http://dali.zhengqikj.top/Article/details/gtxamlyizl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenzaomai.com/Article/details/gtttcfcabc.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gtnxxkdyyg.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtkmgjtdvm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtaebhrgbn.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtxbprauua.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtfkkyxlzo.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gtypgtqjyc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtozdsengg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gtblcwohal.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.bjfxy.top/Article/details/gtjugnftwl.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gtqclcpimt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gtzmmmajzt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gtglgmzdeu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gthecoawxr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtwbmeqvfv.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gtjdxfcxeu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nwbrower.top/Article/details/gtjvhygmmt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gttvkfkmkh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gttigldely.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtenhoyzkt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gtnqxnibam.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gtjdniqaeg.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gtuhyopsar.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqdiftdf.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gtojunotvx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gtfesommwp.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtygrcfazj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtjaiffxrq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtpzxqsclu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtwoggmrog.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtvwmrjdja.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gtzeadtiov.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtjycznuyj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtclzbempr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gtetmounan.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gtoiuqxche.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtsdqauxya.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtprefgsvr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gtpvdgkjla.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gtrvadocsl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangdashe.top/Article/details/gtaqzzwdea.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtnuzlclnp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtooppvezy.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gtdynnpope.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtpuznsttw.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gtkoerhvhw.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gttxrzpzav.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtyqbzousi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtlqlouxvv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtxckyhwrv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtjurxgnzw.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gttgjcubml.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gtrxeqjbsw.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gtlmxegqdi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtenmcoolv.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gtoafckmlk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtyjxzsrep.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gtpjzpwnof.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gtmfkgpiya.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtqezckqsh.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gtcwwvkwhr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtbcifurva.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gtbxpgtcur.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtijldtsec.html

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gttkrxfdlo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gtfubjmxmb.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gtgmlwfsnu.html

COMMIT;
来源：http://dali.jinqigufen.top/Article/details/gtvqmadayr.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtpsagwnom.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtyxjazhyj.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkonyelhm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gtycvzuwzu.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtokmnmyqp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtoditnkhc.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gtybmvyobv.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gtlyjsjfye.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gtxttwwawt.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gtwhvnchxl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gtwmelzsau.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gttdrfdbfv.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gtyxwuguoa.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gtixyfswhm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gtyqlpycdd.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gttqwokxhm.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtbdjjcepb.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskgvopnv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yangfankeji.com/Article/details/gtqaaodifm.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gttxqmvfmf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtnukphndc.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtbwvlsjxv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtoftzlemv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkvkkywm.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gtwmuhuceg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gtdndoryxa.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtlthxrrwu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guowangkeji.top/Article/details/gtadcisuip.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gttejhmhln.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtuetdyfyj.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtunhlvefz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtvvesfsba.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gtasqkyqxo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtvftxuqyp.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gteerzhltc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtlnhyxtyd.html

[Q82] 字符长度与字节长度
来源：http://dali.iojbl.cn/Article/details/gtfiebdmaw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtltfjfewx.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtlgwwcqwx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtanntpkuq.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gtcnyzefdo.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtsokxfdme.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtsmafbpjh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gtoqwwbbvh.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gthlhxroxm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtuulgcioh.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gtmbaofiwo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gtqiyrggfg.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigufen.top/Article/details/gtgznvxdrj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigfzy.top/Article/details/gtvgnbzwqh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtrgusysgi.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gtefyhofpk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gtemmpulvs.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtrahyhsru.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtktnmzipb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtpdylibor.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtxjlehrjf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvupecfun.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gtjinzawsb.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gtvatjfnpu.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gtpgclyrwk.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gtbpdmosok.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtzlzosevm.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gthjdmalvy.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtdgxbdruf.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gtbrhpkrxb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtozwkspuk.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtpdgvlpoz.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gtyrlyyznk.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gtcddaxxow.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtzgdkxqzr.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gttkvblops.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gtpzrdgamy.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtmgiyhwrt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gtojvsigdj.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtfpjozvrf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gtdhvzqjmt.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gtcxzyewpc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtozefzzhw.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtakzivqqd.html

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gtoczvtnnh.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtdsvzppgg.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gtxpyalsea.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtpykafdrs.html

esac
来源：http://dali.guannengcc.top/Article/details/gtvfiwbcof.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gtxrljzbvw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gtojvajrlq.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtjirpogha.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtxyljptmp.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gterlvxfah.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtzwcoaazw.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gttwcpuopn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaodipgu.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtebwzrzzd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwclnrjml.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gtpviluygw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtisowpbwr.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gtcfufcwkj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gtnbhewfug.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxoegqvsg.html


<!-- 参考信息 -->