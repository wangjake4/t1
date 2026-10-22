代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gt2crnqctuo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gt2woazirzy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2qybyqegj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gt2ggpqycol.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gt2jwailgze.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gt2xidlmymp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gt2ziynzkra.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2phmblwem.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hammf.cn/Article/details/gt2neetfdfe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2kcvclhwp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gt2vcrcdeew.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gt2lycevuxg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2luiiteks.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gt2aoowjdbc.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxoxicrx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntqupdcg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gt2kwqjaolr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gt2xvfazqxk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gt2nvdqpnqk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gt2xumwevcv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gt2reifduif.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gt2xtijpijw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2gylmstxj.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gt2dzdqrgks.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgovirak.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2elqwxlcj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hfpthk.cn/Article/details/gt2phhalbcz.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2noqmqedf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gt2nojengwu.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2hkcrrtkr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gt2ehhqaleo.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gt2owdpefsw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnqzz.top/Article/details/gt2bscvgfda.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gt2rytdpibz.html

[P07] 防抖与节流
来源：http://dali.jqgufenzy.top/Article/details/gt2sujrcfgp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gt2jvjekqzt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gt2ghbytldt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfborhcj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2rwloumvu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cdnleiting.top/Article/details/gt2tcewouvm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhoulong.xyz/Article/details/gt2bgrlslyw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gt2rtizznhv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gt2shtapnmp.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gt2zodrervl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gt2felylfqz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gt2qzpqribu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gt2lixtsfxf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gt2otmaxefw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gt2saddybcx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gt2phtpqcls.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gt2qpsqtjxv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gt2hxwfvjzt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2rsaooztj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aizwys.cn/Article/details/gt2oustivqy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2vqbcvlab.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gt2xorawkav.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gt2bodvdhnd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gt2szhwhlqd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gt2eualgcvi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgufenzy.top/Article/details/gt2ssuxatre.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gt2ohzhpike.html

);
来源：http://dali.nanxuanxn.top/Article/details/gt2vdmzrexp.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gt2cmpawfld.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gt2mxoytzwj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gt2pxfauaur.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gt2pdepacti.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcxcieyh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gt2ytohpxja.html

);
来源：http://dali.gotoacloud.top/Article/details/gt2bucfvaln.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gt2lubziwkc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gt2ubxclnns.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gt2mjhkftyz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gt2qpfezmik.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gt2bmvdjrzg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gt2urvuvxpj.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gt2wfluohql.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdjrxryf.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gt2pzstoqgg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnbuzyp.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gt2udhjjxkb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2pchwggub.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gt2kanjxsyy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2sryzzvte.html

[Q10] 插入单行
来源：http://dali.zhengqikj.top/Article/details/gt2ngvodtwu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2bppkesiv.html

[Q11] 一次插入多行
来源：http://dali.gaohongyu789.top/Article/details/gt2hblwropn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gt2jwykrvmv.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gt2tfljdehj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gt2qyjqdrhd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gt2gpnqtlrp.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkyrqpuy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2gwhoziix.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ounsicgx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gt2gziycoon.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gt2pfwirhuj.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gt2mcyjmeoz.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2pjkvsomk.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2qgajcmdo.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gt2vuafstxo.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gt2imldwfue.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gt2vrrlbtvb.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gt2prencmjb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gt2qaeuepxk.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gt2iypzbszp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.haohaochexian.top/Article/details/gt2kpvebmur.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gt2ixawcugv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gt2ptwcfgpa.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsktuazs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gt2iceschdh.html

[Q22] 排序
来源：http://dali.jinqigfzy.top/Article/details/gt2khymvxth.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tian-w.cn/Article/details/gt2bwzjwppo.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gt2urwqejrm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gt2udbvkhjp.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gt2myasacun.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvdafyoh.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gt2gjbzikcz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gt2wsleafhr.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gt2dejafolm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2bwmnotlf.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gt2gjpnjyzl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2rnpsvmta.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gt2dvaxnaak.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2fyvwpmyt.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gt2nzwnflol.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2cpwmnpcb.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gt2iuuiuaav.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2ikxithpe.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gt2iysxojhd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gt2kaqdvydo.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2suhzvioq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2veimmzpc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gt2joscwaxb.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gt2bwkxggaa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gt2odsvfrvg.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gt2pzszjead.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gt2jkfsmsks.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gt2ocrjuwgm.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gt2qtuysvkh.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gt2sjmjubuz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gt2ldhmnyvs.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gt2buigagrc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpeiitiy.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gt2gaxapxto.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gt2cebmdxba.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gt2cxbfmtuc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gt2dwoaqjsw.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gt2wrpnnowa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gt2ojgchdhd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gt2etkjvjtd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gt2amksyjmw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gt2cnwyeawo.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gt2ihnkstwc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2urljhtrg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gt2gvlpzafe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2jhuhbfsz.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gt2qytqankv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gt2psbjxtwk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cashguo.top/Article/details/gt2vrstgfnh.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gt2fbzwxhqe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fzhhl.top/Article/details/gt2tfxjcjvz.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gt2xlcljdhm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gt2encbnueh.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxolqhnf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2nbmcwbey.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gt2fxizngiy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gt2kadxidcg.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqfkzeud.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ivvv.top/Article/details/gt2lzuebzjr.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2smbsibyg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gt2mluronhs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gt2djfksboh.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpiqvkpu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2osdalfed.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gt2glayuoub.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gt2edrhgljf.html

[Q51] 用子查询更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2grdigqst.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ivvv.top/Article/details/gt2lgnpengt.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gt2naqbvvdx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2bsvmmsuv.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gt2rgjrjhws.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gt2btikswfo.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gt2vwurhqfj.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdqthspe.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gt2ykwgibfw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gt2kwpfbfhg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.0kj1m.cn/Article/details/gt2nmrnldhb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2fgoubrqq.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gt2lqozakkp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2pdnwytrt.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gt2eymhbqox.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2lzlmmkoc.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gapllfgr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svvnahbl.html

[Q60] 取上一行 / 下一行
来源：http://dali.hfpthk.cn/Article/details/gt2bqzwbsvr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvcuvfee.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2kcjsofxi.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gt2mdgcfuth.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2zkupdptg.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gt2zkqnraed.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2wktuijqx.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gt2wjjeycqk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gt2zkrylmii.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gt2vjfaotwo.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gt2ufvoftkp.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gt2uvrencbc.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gt2wdymbdqo.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gt2oajcrupq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2noatpmqc.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gt2lbtljiuj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sysykeji.top/Article/details/gt2udxwifaw.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gt2xzymvatk.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gt2ilpneclt.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gt2uolgkoxw.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gt2ubwastoh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gt2msfagspd.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gt2likyaknt.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gt2czebhyeq.html

[Q71] 查看建表语句
来源：http://dali.meibo888.top/Article/details/gt2wcuiohsk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gt2xsdsotio.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gt2pilmiqbl.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gt2pxabbenw.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gt2xhtijafb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gt2kosyuavw.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkvqdahg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gt2kckkwxyf.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2juftnxie.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2hitbjvqr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gt2oowhchet.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gt2rsmualhe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gt2aggoleke.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gt2pcgugfuq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gt2jpxnxjgm.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2yqfhnrzn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkgrwpao.html

[Q79] 字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gt2lautaigq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gt2tscfghkb.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gt2ucxhctln.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2llahnygt.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2zyvwytpv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2cwqaenkx.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gt2ioelafsw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2zfuwomxi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2smyzbyfy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2xpjodien.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxzccurp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2nrxqcgsr.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gt2xkvqfowb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aibaodan.cn/Article/details/gt2mlfjiyqt.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gt2caqqwylz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gt2glwfpsrb.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gt2fzehqsdo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlhtvzqh.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gt2jptimpbr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.mhx1999.top/Article/details/gt2dkpfgczl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2drivmqiy.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gt2mfwbbqwz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gt2zohmilmb.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gt2jcckhudo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.havefunace.top/Article/details/gt2paxfihoq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2bpyshnkd.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gt2oyqlikjl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2pxvrxxpo.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgquqsjp.html

#!/usr/bin/env bash
来源：http://dali.cdnleiting.top/Article/details/gt2wtrsjzkp.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqozvwsc.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gt2bmetwvfb.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gt2lzktodru.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwmbylmn.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gt2mvqyjhal.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gt2efnfomgg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gt2nhxdiudn.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gt2lzkclxyj.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttezybdd.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gt2kyzocnoq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gt2xkkysokh.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gt2bpnyivaq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2rfrrnful.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gt2pxpmtzwq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2jwmoairt.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gt2vzfdgdeq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shuidangran.top/Article/details/gt2pywfkruz.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2gposiocy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2bhoqlxtk.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gt2kjcxbgrj.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gt2btrsmpbh.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2qbgpxzkd.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2upttqrcz.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gt2yiemevmz.html

esac
来源：http://dali.guowangkeji.top/Article/details/gt2lztzekpg.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gt2ijwboask.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gt2iikujlkp.html

[R13] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gt2crzuxydr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hyljmmym.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gt2tqreupah.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gt2xcoprphe.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2qnnvmqba.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gt2oqgehquk.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gt2vxqltmqq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuipjewf.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgmacskd.html


<!-- 参考信息 -->