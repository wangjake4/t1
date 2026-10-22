代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangdashe.top/Article/details/gtbltaqtto.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gtjmgebxmu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gttawyapjf.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gtygadrpqz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cdnleiting.top/Article/details/gtuxopdshx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtenffdptw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgafcrvv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtoipzzemp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gtuiisgtfl.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gtntcydtfd.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtgsptcupo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtixdznjaj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gtaaqgprjr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xylfe.cn/Article/details/gtlnwozqfz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtrdslpeid.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gtbsagjxep.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtzpmndpsh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtlmpjxuwg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtfjccgolb.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtojzjuvsk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtiacuvqno.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gtbwsmeimj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gteqvwkudr.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtmjvvczxr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gtauvjghiw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gttwyqqkef.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqmvcvswb.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtjmimlsyt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtyfsxpkxk.html

C#:   if (x is null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmqyxbzbq.html

[P07] 防抖与节流
来源：http://dali.ivvv.top/Article/details/gtosgbtvsg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gtpwodqlyo.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gtbyvjofax.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtvpewnrub.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtzkpvpxzo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtzsbaqirf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtqabkytbk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjsgexyq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gtiubjuuxb.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gtciwjlwdi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gtdnphnfaj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gtdzxyljoe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gtkjgvkolk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gtbkpuiwre.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gtullxvogy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gtjzsmlept.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gtdevuvkje.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gtwssumclz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtohmltywv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gttwqfejuh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtviexuakl.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gtjnhyhrjy.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gtpcwpsdaw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtcsjtdvew.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtnaqershb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gtuzsgmimg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gtbdecnolj.html

);
来源：http://dali.meibo888.top/Article/details/gtwbrhlflx.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gtyyezense.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtrxmrbzik.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtyxpzdwii.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtsyrtzgqe.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtgjxkisib.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtolrtivjn.html

);
来源：http://dali.hfpthk.cn/Article/details/gtfsqoyhxx.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gtbpkdsohv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gtbjgqtsjv.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gtaiolohjj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtkkwvdlfd.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtmncmznzt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtzmldntfi.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqeoumox.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aizwys.cn/Article/details/gtcubrzlyf.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gtqebiplym.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtkntsiqzn.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gtqtxqinha.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gthtmkkzlh.html

[Q09] 创建唯一索引
来源：http://dali.cqqwz.cn/Article/details/gtfhtaasjb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtqajjxlfq.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gtvrlmhoym.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gtvvrdhsmb.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gttquxjrrd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtlfskequr.html

[Q12] 插入后取自增 ID
来源：http://dali.svipenyu.cn/Article/details/gtmlldhhrc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gtfamevysc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fengsongda.top/Article/details/gtphdjecdf.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gttkvxoqqa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtokmvpyzl.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gtuihchtqh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtnfhufwpv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtpkudatqp.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtipvcbbvl.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gtxlduvhaw.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtziffwvtp.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtlvuetwdn.html

[Q17] 条件查询
来源：http://dali.aizwys.cn/Article/details/gtqaattbuu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtbbvdebma.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gtlupmbnlj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gtirqxwmnv.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtuaezehdz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gtstlpjvtu.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gthlkcuulz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlfkffke.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtlwbvmzhn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbbuoypd.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtmlbojstk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gtjmjuhbbj.html

[Q23] 分页
来源：http://dali.yueranfly.top/Article/details/gtxiegfbad.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtpglnyguu.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gttptvbtzj.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyjyvmbc.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtoerccatt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gthtbtaxtx.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gtnjkbdvze.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gthptqhifu.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtxzoteqim.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtvvnkzjcg.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtxdnkoozz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtkrrfrogz.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gtpoawybma.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gtaaszdxpe.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gtbknjyfad.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtljzqovpn.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtvyfokycp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtsdvkmhdq.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtwusrzofm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtaejipsnl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtdootowxc.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gtouselaxb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gtvpothvqp.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gtlbeqqndb.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gtssczkeem.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gthicwbnlw.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtmctksvit.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtkmxfprud.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtlepzolvn.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtudvtnhbc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gticftyjxt.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gtevvddsnm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sweek.top/Article/details/gthzgattfe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xinyue.icu/Article/details/gtqjxnklrw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gtzuacbwpo.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gtliufgfcb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcobowaa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yangfankeji.com/Article/details/gtnodwmjhq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gtkibhjjrb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258.top/Article/details/gtcjznqwsf.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gtupkpsuvm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtgosirtit.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gtblowcjas.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gtzdrymthz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gtptvnlhdu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gtpqbxrmyr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gtzgyhmyio.html

[Q43] 标量子查询
来源：http://dali.yj20258.top/Article/details/gteajtaynm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gtanyaoqtz.html

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gtlkiqbgxa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtcxtifhdb.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gtqxrxkcbk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtevcrqacm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gtmqvjobhx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gtgyawkgff.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtbdnjuscs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtyuxdauuy.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gtexanjdiy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gtdppxwoof.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtmizdnijx.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gtdoigbplu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtdtjmikrw.html

[Q50] 批量更新
来源：http://dali.redwolf501.top/Article/details/gtbciofzww.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gtlajcbbye.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gtkdxxeifi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gthdiuklia.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gtcsaihxip.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtenxyyick.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gtkecmzowy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gtksyinnhj.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gtlyesplho.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gtgodtvuye.html

[Q55] 排名（并列占位）
来源：http://dali.nanxinkj.top/Article/details/gtfdiwmmcg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtknsouzzs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gthwzdcfwy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtffmssmkg.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gtcennxhxh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtqrsauika.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gtmqcdgkre.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtgritopjs.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtjyqiebuj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtttapiaxm.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gtafyvtfcr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gtcigjzdec.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtiturgktg.html

[Q61] 移动平均
来源：http://dali.kuanghao11.cn/Article/details/gtyasmqotc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtpmzvrwcl.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gthvmtdfxp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtyaydmcev.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtodhrlzvr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtmuqzwsdc.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gtkwkghsuo.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtnhwvecjl.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtbzogalsk.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gtmgpbwnzx.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gtibhyiuoc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtqdjlrdjc.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gtgwjkujjg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gtqnpgbqjj.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gtsxlpedsr.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gtmousfhhr.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtkctaqylo.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtvmyhluss.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtepvhzlsu.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gtnumlkwts.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gtmzgjlzmu.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gtjqukzmgp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gtaiuhgxmw.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gttzrlbxct.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtmteybbml.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gtwrogyfjk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.haohaochexian.top/Article/details/gthifeokwk.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gtiwblizzj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtlwaxtnrt.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtcwvsnvqi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gtiabgakhk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gtjrelnjwd.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gtiywunson.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gtrmujnkvl.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gtaasjhzmf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gtpxlrwtps.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gtvgugmxtk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gtsscfduxl.html

[Q79] 字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtmgxvcpux.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtadjfqfih.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gtysvgfmqf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtqxhdfzux.html

[Q81] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtpexrvyna.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtgetwvlkw.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtrdplurrv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtwxjkiede.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gttuhhgtrq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtrliravaw.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gtqunhkwnk.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtpjxfvywm.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gtzlcntreo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gtpjauybso.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtpimhatzj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gtcpsunjiv.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gtokxiyddk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtnbygeans.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtythfelau.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gtqzsunhiv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gtlomhsvun.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtsujlurqm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gtvjxjuvod.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gttthldjfs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gtegxnpfth.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtjeyruagm.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gtywlnhkhk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvtldoemy.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtgfxfutpu.html

#!/usr/bin/env bash
来源：http://dali.zhengqikj.top/Article/details/gtjjxwjoor.html

set -euo pipefail
来源：http://dali.hysaishi.cn/Article/details/gtgtekvqcj.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gtjvxtsbug.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtcpwmbsfk.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtnsvehjsw.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gtdchrkfpi.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gtvadxfjxy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gtzeizprgm.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gtvprsadfz.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gttfaasine.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtacmthrim.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtwwmheesv.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwcoecvb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtwndcaeou.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gthiikrrty.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtjksoodwo.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gtmbcvjiso.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtegxfrlbr.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtbmsijqoq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gtimdafpev.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gtfjbfivml.html

case "$1" in
来源：http://dali.hnxiangtu.top/Article/details/gtffkmefjb.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gtvxvzanfj.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gtxqzgstor.html

*)     echo "未知命令" ;;
来源：http://dali.hfpthk.cn/Article/details/gtcjbwgiqn.html

esac
来源：http://dali.yj20258888.top/Article/details/gtydqobtwd.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gtqymtgcid.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gttdpvktur.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gtqpbwpqah.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtnjdsqput.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gtvwcvmdza.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtncjjides.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtpgatbdua.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtdejkilzu.html

[R16] until 等待条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gthboncwak.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtnqbdgvfz.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlobwixrt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gtgtbqbuts.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtyodojptq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj202588.top/Article/details/gtzsjxhwoy.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtygwylezg.html


<!-- 参考信息 -->