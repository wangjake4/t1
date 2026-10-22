代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtogzmesla.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gtqwmntkbr.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gtqivutjit.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gtrriqrfzs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gtnlyacyhb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtrptzplap.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtuentgxjl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gtebkcdmwk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gtzityqmha.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtlzazcwmu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtsnxdcdak.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gtghhtzcaj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gtgltlhrto.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtuwxllfol.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gtqywxmwoj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtsetvuomo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtctsycllh.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtrkpbehpj.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gtaerlhnsf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gttllkwkkh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gtlhhigcgw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gtzpfzbyhf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gtzrucrauh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtrloqgbxj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtcqkrsvff.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gthtekoooi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gtvvdrdfbx.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtnjksrqqo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gtmldqbgcz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlftqddnr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtjbdnqgtj.html

PHP:  if (empty($x)) {}
来源：http://dali.gzhubu.top/Article/details/gtdebtfwij.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gtsbddmlgb.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gtutncwvge.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtksycuuve.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gtqvxbqcwm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtzojbmrmo.html

C#:   if (x is null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtuymmylkj.html

[P07] 防抖与节流
来源：http://dali.ivvv.top/Article/details/gtehmimlac.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtsevylits.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gtlaqodgtk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtitddkjad.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gthovqgjsb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gtjweuobss.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gtwxxzizql.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyyautpe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gtwqgigxwx.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtfrqwbfuy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gtlzcazbxc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtsjfjsyxu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gtuoiimbxj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtkoaacbhd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gtxkcakaze.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxgqkybe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gtdakjqddw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gtvvkbzrvh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvqauxfsw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gtpznqibbs.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtoycpmrdc.html

[Q01] 创建表
来源：http://dali.gotoacloud.top/Article/details/gtseawlbbk.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gtfhvzukgv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtjzpvhqry.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gtypmbiajo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtbosqqohh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gtqdvdudmu.html

);
来源：http://dali.0kj1m.cn/Article/details/gtlzmafuuk.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gtqjfgthvv.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtmqlsvtpf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gthdzxsyvm.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtsqrzmbiu.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gtvmayyhme.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ybcxt.top/Article/details/gtxyhrbqmy.html

);
来源：http://dali.ehwqpu.com/Article/details/gtowbybqfs.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gtboyowiij.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtllaxpajf.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gtpujxcrjj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuanzx.com/Article/details/gtwdvlccke.html

[Q05] 重命名列
来源：http://dali.fzhhl.top/Article/details/gtobaftwku.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gtrfjwvegl.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gtsuxtihxj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtpargydcx.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gtyxctoixd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtdqfyjyis.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gtgldabkqi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtuyvhckeo.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gtfsfseuzv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtpoxngguy.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gtohljwkcu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gtvjxgucxx.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gtytodqmun.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtjamxsmzq.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gtxjbtvrqk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gtthcpswot.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gtiydptmgk.html

[Q13] 忽略重复插入
来源：http://dali.daria6918.cn/Article/details/gtiovzaynl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtalqrylop.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtpnehvzrl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtyuaarorc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtawvxbepp.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtxtiplfyi.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gttzlycvaf.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gthbborisd.html

SELECT id, name FROM users;
来源：http://dali.smart0.xyz/Article/details/gtprgowusb.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtshcxvgqb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gtnizfwjkn.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gtjtbvjqhz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gtzdfumqka.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gtyjgetoqk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gtelphzgri.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtieeikzbc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtowsmxjrw.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihftenbt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtgnkwthes.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gtwwvxahyw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gtuyharsso.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gtrwnzfcsf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtxxusyedw.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtcoidkbar.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gthidecndn.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtbpbferss.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gtwkyarjnj.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gthzboqbpv.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gttoilbore.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gttbvrgbxc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gtrahobppn.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtavtleuhm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtwgoelbrr.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtnnctzism.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtmvengqlx.html

[Q30] 分组统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtapxjltso.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtmfbyccpe.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtbpaagsqm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtvbhvwuhp.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtfxuqaivt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtxakkrbsl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gtyvuanalx.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gtvfiuoypc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gtxlmsfqgb.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtbfiosati.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmxwlhjq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gtzvwpmusx.html

) t WHERE rn = 1;
来源：http://dali.cashguo.top/Article/details/gtwyhuhnxd.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gtwuepgfpx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtpzjbqsjz.html

[Q36] 左连接
来源：http://dali.c1oappe.top/Article/details/gtwdphiiby.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtsosrbpoq.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gtfqwqvlau.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvkecdzm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gtuikwjowg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gtihlfvtvg.html

[Q39] 自连接（查上下级）
来源：http://dali.svipenyu.cn/Article/details/gtfisamrvg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtxyawxioc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gtdhdnukvw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gtirgokzit.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gteycxvzlb.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwoilxwp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtlodyrciu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gtmyzhjuer.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtxnqgitqf.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gtzsmuszno.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gtqephtzfj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gtnxkphfhq.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gthpkzwrzy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gttvaehnpz.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gtpjsibfut.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gtazcuwsyi.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gtxhtntior.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtlqrxtcyq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gtwjbkyxhm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtmaifuqbl.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywnuickq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gtvcnjpigm.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gtsjjpwzce.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gtjaarthmy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gtjjyymwox.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gtqqngpviy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtcizlhsfo.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gtyencyrjm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtiyrvkmur.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtxhknopxi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtfknteqjs.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsejpytp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtdaexhwuj.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gtvhdnygso.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gtiriasigd.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtescliufk.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtecukyqzg.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtvdjcunuo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttganukyq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gtugigiyge.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtreasebbg.html

[Q57] 行号
来源：http://dali.meibo888.top/Article/details/gtrgiocgyb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtdiyylgxu.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gtpixzmhcn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtnyiuzkrh.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gtwryijvxe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtimlemkpc.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gtfafeipsg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtxkuyphzo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gtxojmvzqn.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gtyzxzntzu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtapbtesdg.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcatzplwb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtlbnjhhim.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gtysamtsou.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrkengpq.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gtahefrmal.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gtlspaxmsc.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gtafkwyoxz.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gtmtecyetv.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gtcvqrsmzf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gtmouhheiq.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gthzksjxlz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.redwolf501.top/Article/details/gtouqmyxle.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gtxnvurjuf.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvdmmrwk.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtvgbvpftw.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtqcmxszeu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtwnvfrwng.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gtzerghxpu.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdvoxxls.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gtgipgmabx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cdnleiting.top/Article/details/gtvlkyeehp.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtedmekaok.html

SHOW INDEX FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtwwxzelhg.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gtrmgvagcl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gtqivhovyd.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gtmcyjjxif.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gtsiecnwqg.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtcricbbkt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtlpwlwbsd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtmarcwfun.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtagxoytkl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gtdxnzjabx.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gtkqbelblr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shuidangran.top/Article/details/gtqrydeete.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtkutcufsf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gtpwztmvzr.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtjkljpbwb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxfonmty.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtdnvdwbpl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtupepiedf.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtqtazdkzv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gtgfbebner.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigufen.top/Article/details/gtnegjyouo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtbpfuzgei.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtqfrogsoo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtwkcslrmu.html

[Q84] 去除首尾空格
来源：http://dali.vqdsnc.cn/Article/details/gtcuqpaniw.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtbwifdhvq.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gtzqgnmewz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gtuxerlolv.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gtkegnhixk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtpbtzpjgx.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtvwfguyxx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dianchejie.cn/Article/details/gtnvxmwgst.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gtorasocyd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtqhkbppgs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtfbugrtfk.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gtcfghrjxk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtvuqyefnw.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gtbdosgyva.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gtxuvlkzhn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtciffktfv.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gtvibteemp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbdighgtf.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gtepipzswb.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gteqxsjedf.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtahdkfttd.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtxgxihmnp.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gtuzkllyql.html

[R03] 只读变量
来源：http://dali.ivvv.top/Article/details/gtvinxdofz.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gtztsathak.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuzulkmz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gttzkdjljd.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gtbkhzoohx.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtoaqounzj.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtzumojluo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvfyukpgw.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gtfftehikz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gtqwvyymqw.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gtlbogepqb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtmjohdkaa.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtubspawda.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gtoljouptf.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gtuzfhlvkc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtwvfqjnbf.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gtuhgwufgy.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtnlpgneic.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtfhbpqryb.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gthzsocqoq.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtupbluemb.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtcmexivdb.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gtyqepoqno.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtrodcyget.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtkcmrjgyb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtteamgypd.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gtcigtgndp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtsxdtvxti.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gthdscidxn.html


<!-- 参考信息 -->