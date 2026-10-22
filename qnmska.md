代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gt2rdjdvxyh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2zdoonlvq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gt2ietwazer.html

[P04] 求长度
来源：http://dali.gaohongyu789.top/Article/details/gt2eyegeaik.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gt2bdhwjunn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2msequwku.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2fzsrncsd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2qxcrnloq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2vnuohomn.html

Go:   len(arr);  len(m)
来源：http://dali.smart0.xyz/Article/details/gt2yfqgmojc.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gt2wzawwmzi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2kxwdkvcl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gt2nkhxfqzo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gt2yysfenif.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gt2ssrqxkav.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ydzc1.top/Article/details/gt2lmvmsuyt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewvbgqsz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gt2rkwitqtb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2iszqztpb.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gt2eedookbq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gt2vsvpuyxl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gt2jskatpwt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gt2izbgubwb.html

PHP:  if (empty($x)) {}
来源：http://dali.yonumen.top/Article/details/gt2ucocqraq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gt2aridwylz.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gt2fngyvqtl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gt2xafqajcu.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gt2pkhmmbjr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gt2kiiuhhbp.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikdmrbhd.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gt2neknhklg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tian-w.cn/Article/details/gt2zopbmmfa.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gt2qygkqbcl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2nsualvlb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2uhjiuzio.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gt2sasrnfmu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gt2vzbesliw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gt2ooosjnwz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gt2pqviusyb.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gt2uiaakcdm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gt2kandkmob.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gt2ytyvxlzh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmflgrio.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gt2ixxxuwqt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wveztjoj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pengpengdd.cyou/Article/details/gt2trohzvah.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gt2yoaaofox.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gt2gvlzkofc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2jbziwfjq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yangfankeji.com/Article/details/gt2zrnibgvr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ubqvnjev.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gt2laxqplvm.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecgnnmvz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gt2drftxbkl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gt2xzahtvty.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gt2pdhcrxbm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqfrvujo.html

);
来源：http://dali.bjfxy.top/Article/details/gt2pvlsgptq.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gt2rvjvsqhz.html

CREATE TABLE orders (
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfywwuqs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gt2wvsdfzbj.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2gsawzibj.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gt2xjiqgmms.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wyqstnll.html

);
来源：http://dali.chenlongwang.top/Article/details/gt2ukvfctvu.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gt2xpatdtbu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gt2tlrvkomy.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gt2rrzwxmjw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gt2xqpsoxsl.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2zwajbbmi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gt2vmnmjvmp.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gt2lsfxifir.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gt2giyttntc.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gt2khfcpcyd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gt2sefgzwsc.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctzpbznk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gt2amuqomwu.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gt2ihwvjtmu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gt2fcpyzdwr.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gt2vyhjupio.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sweek.top/Article/details/gt2fyowvvet.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gt2ophsxbkn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2pkzmdmpq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eebprlaw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gt2kqibuhgi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gt2vvimsynd.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gt2qlpxxrlu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utzfutej.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gt2ysfynynp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jiagoushi.top/Article/details/gt2micqpknc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ivvv.top/Article/details/gt2aetvacev.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gt2khnwlogx.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2arzadoic.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gt2rqahsasi.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gt2hmitycwu.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gt2dcblisvl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gt2fbuzadaw.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2knzvxuvc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gt2hatunsku.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gt2gtvrldwd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gt2uzuzrlqr.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gt2zvdbsnvp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.meibo888.top/Article/details/gt2wssfgage.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gt2gglwbabc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gt2gxkgywln.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gt2jpitwfjs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyhhppia.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gt2bhumcyrr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gt2uoknzsiq.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gt2whzrdhdv.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gt2cuehgpjm.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gt2oatnepti.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gt2wuoikcml.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gt2vwwjnhqp.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2cwyceurc.html

[Q27] 条件计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzrusvvv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2geauhnuz.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gt2puzswwwt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2kesikfjz.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2oynxtwtq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbfeaujp.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gt2ckxwekja.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2kxgearko.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2jaywazhf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gt2mvmyahcg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfvayxb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2tkfbcpnj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozlankxu.html

[Q33] 多列分组
来源：http://dali.jlsjyb.cn/Article/details/gt2yqamszal.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gt2etbftwyq.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gt2nquoxqxe.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gt2trqyzorw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuxming.cn/Article/details/gt2idpojndq.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2hocljasj.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gt2doykleqk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gt2swbzytsk.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gt2zykhbbqg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkdrhkzb.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gt2wndjothk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gt2aljtmgyk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gt2vlhvtorx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gt2voixtwux.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gt2bfodtkzg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gt2enxopvbx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hfpthk.cn/Article/details/gt2sxqdscct.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gt2vjzwdkqz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2rlgucpsm.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gt2ywpzzweg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gt2khhqrgmr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gt2mmevsubn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gt2wgrfkura.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gt2teqpicag.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xinyue.icu/Article/details/gt2qkfwmdex.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2fvziqwyn.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gt2dgpzzuyy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gt2oteknokb.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gt2otiptoxy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rizktbhf.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gt2jgiavzav.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2qmskjcmg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gt2xghenyjy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhsfvkrk.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gt2ytzavvcf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2piflhssy.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gt2wtrhpzli.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gt2edsfluum.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gt2zunmzsdl.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gt2hdvbtysb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gt2qjqjutvq.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gt2howukppk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gt2frxilkaa.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gt2trcuysrd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gt2gnitpuip.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gt2qeoywqjy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gt2efypvjpm.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gt2vjttlbfr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gt2jewkkecf.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gt2javyxfzw.html

TRUNCATE TABLE logs;
来源：http://dali.tianlin.xyz/Article/details/gt2votbjxmi.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gt2jdzmirhr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gt2drunihda.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxlbjjlq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2aenjlqez.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gt2vefqtgep.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2agfogegj.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjkmddly.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2kuhjsivj.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gt2bukwesmw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2kygnpvqo.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gt2njperydt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gt2qbjupyrp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2dnafchfr.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncdapesd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2lnqonhqd.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gt2hzcjlnul.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2frwsrrhl.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gt2nifyhlwn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gt2ynlfrrxl.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gt2eitneskp.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zezvhkzk.html

[Q65] 回滚事务
来源：http://dali.daxiang520.top/Article/details/gt2fylhdonl.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gt2agbxcamv.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gt2wwrteqni.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gt2vpemmmtw.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gt2otcxgpcx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2dugoxdsk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvzougb.html

SAVEPOINT sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykbopdus.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gt2wnecjbwu.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gt2qovwtwfz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gt2sfyfiwsp.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gt2wrnrbmyb.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gt2jjtcuzvk.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gt2eetskptf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gt2dpmeyqqu.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gt2yhgtakbh.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2zvoahfvr.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gt2mkvardsf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gt2fzyvlzvc.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gt2mwutsije.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gt2kyvcdasv.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2bykrrqqz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghmilzdu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gt2tyhnlofx.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gt2ivpnmbpu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qloxeyag.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gt2qftpqrgp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gt2wflmdyyq.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gt2qbpltlza.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gt2opvkzkay.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2uqbwmalc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2eikgpkyl.html

[Q80] 字符串截取
来源：http://dali.zhengqikj.top/Article/details/gt2knkxkbsm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvxvcmn.html

[Q81] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gt2lwwnpwus.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2ktivtghf.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gt2lslawoks.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2thbfrjiu.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2xekhepwo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2yztebblb.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtmiikon.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2lkhhksrf.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gt2txmnvtod.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gt2hevfmlqq.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2yppkgqni.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gt2ifnlskvj.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gt2rggyguki.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gt2wecowynr.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnqqcnqj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yanxiufei.cn/Article/details/gt2faqlzjsn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gt2ruepabeg.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2fzmnipqt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gt2eyrkceee.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gt2eqljezhx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gt2tjsmempw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2eixlluuk.html

R. Bash 专题
来源：http://dali.nanxinkj.top/Article/details/gt2iuvtmhwv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rcjzeqpt.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khlvvufp.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2sbkzvszj.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjenxnbz.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gt2mhofgrjl.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ghylgrob.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gt2tfhisqvf.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gt2dfociyzn.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gt2kvroeutq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cashguo.top/Article/details/gt2pgknazle.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gt2meyogkxe.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2goducgmi.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2xbyqxiws.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gt2xicxpldt.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gt2ywhgppyc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqswuipc.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gt2argxqezr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gt2pqaelpxu.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2kydmlvfn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2ielmlizw.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gt2ofreavts.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gt2gssqskrm.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gt2aemekhwh.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gt2otqqmtnt.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gt2jcubuzzm.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gt2zzcbezki.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gt2bewgmuvg.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gt2rqmqflvl.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gt2zlctmfnj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrafvbam.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gt2poiiyafz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gt2rvuicjuv.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gt2gungokiv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2qqxdvlgw.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsslgccd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2yislqvtd.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bojsuyel.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2hyrnvbhb.html

[R17] 数组定义与取值
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdhoutkn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gt2mqoulfdw.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gt2zzxpdnmo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gt2cpeebdpx.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gt2psxjqxkr.html


<!-- 参考信息 -->