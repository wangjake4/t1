代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gt2iwvjfzbr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gt2bkdnxbbl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gt2rtsivrlm.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gt2viazdufh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gt2orlzfpuf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2zgndzlsq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2xcwghiwe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gt2pycllhsi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwkqjwxu.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gt2zwfebhsp.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gt2wramoour.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjdwjkly.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gt2morppxle.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gt2lrxlnfil.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gt2hngibepj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gt2ogzhqntq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gt2pmjsigwl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gt2prmvsgqq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2zkuctzly.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gt2limjwizl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gt2oqdwhyby.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzjituxp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gt2zzsbvelt.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gt2lguwlfik.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gt2nsspdysx.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2jicqvdmf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfbqixkd.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gt2pxgqoyiy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgfzy.top/Article/details/gt2qjqkhuew.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gt2zcsaaydk.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gt2xantopzi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gt2xfrvfyop.html

PHP:  // 手写时间戳比较
来源：http://dali.dianchejie.cn/Article/details/gt2xvwdrjum.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gt2pgkcfazq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gt2sfthsxzu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2hlxgpyim.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258888.top/Article/details/gt2imbywetp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gt2fvwestlc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gt2emzjywtf.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gt2scnvqgmv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gt2nruzhojv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gt2hrnwkbtr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gt2mxysebap.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikeyqdyf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj202588.top/Article/details/gt2eraupjht.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gt2mgioeknv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gt2stpmjbwg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.316326.xyz/Article/details/gt2goxubuzr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2uladvdlo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gt2yjkfgadx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2uapayssv.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gt2wpyatise.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gt2mdaiwdfg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnfsuaxp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhmspwdz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gt2txofqyeo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxwgtvtx.html

);
来源：http://dali.smart0.xyz/Article/details/gt2miwtkovq.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gt2hdhzkqkl.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gt2ofxkiszb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gt2sobuyhpu.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gt2kkfxtefr.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gt2axjoajgt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gt2rewynamw.html

);
来源：http://dali.ybcxt.top/Article/details/gt2uzylzjrq.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gt2qsoxrbfv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cucudq.cn/Article/details/gt2oowswwsx.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gt2lyylmhtv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gt2urmxpoav.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gt2cdyxtdiq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gt2mmaldbti.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gt2zpxvhmox.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gt2fumxtfho.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gt2qdacdtsw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gt2xelvlqcb.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gt2oeqmplel.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gt2crbndwwv.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gt2swpuskbq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gt2mcoedomh.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gt2fothvrdg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpfgiasb.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gt2gcdwnljy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvrugnev.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gt2aonyjevd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yvedp.cn/Article/details/gt2nqbsnqar.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gt2byhyrvzf.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gt2rhivavfy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2frgfiosg.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gt2crsvftyb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hywenlv.cn/Article/details/gt2jdepzfzk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gt2xptslqkv.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gt2tbqlsdia.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gt2qtvaopda.html

[Q16] 查询指定列
来源：http://dali.yongpay.top/Article/details/gt2lrthunui.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2yxtnknyl.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqnwudhd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2pzgdnnng.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gt2kfyexvaa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gt2wezburyi.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gt2skrtmwrh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gt2nwpffyrr.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gt2izdjyrpy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gt2aszzbmla.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gt2fhldiakv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gt2jfddfxrc.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gt2rirxrlbs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gt2yeahsqsa.html

[Q23] 分页
来源：http://dali.zhoulong.xyz/Article/details/gt2wsgrkmus.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gt2wvitvgxg.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gt2geizmfyn.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2epgpkdev.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gt2smnyfhhu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gt2oyszrewe.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gt2ipmdirjt.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2srrcnxyn.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gt2ffmqimzb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2rfxaduky.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gt2nllmchms.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2zmdgrxny.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gt2owtjtevk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2jgprvome.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gt2zqrzxybt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2lsprcnud.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqcebtyk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gt2kbwpxwwj.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnwtfpug.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2sncfngje.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gt2eiapaiif.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gt2vnrkiznn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gt2jbagvgkv.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gt2epwalfry.html

SELECT * FROM (
来源：http://dali.zhengqikj.top/Article/details/gt2omdcwyvx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gt2chrlgnjz.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfprsone.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gt2njvmfdwr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2zmcrilge.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gt2qrggjujj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gt2demkvkdl.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gt2cmngufrx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gt2yqkzpnll.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gt2gnogvedy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.havefunace.top/Article/details/gt2zhlykkwd.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2fagpxzbp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gt2agwkpcxg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gt2bkzffdxd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnqzz.top/Article/details/gt2blvkdksb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yangfankeji.com/Article/details/gt2hweafpsh.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2osyrpkzo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cdnleiting.top/Article/details/gt2gxyajybo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbfeebtf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gt2cuzdvyad.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gt2bfkhakrx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenlongwang.top/Article/details/gt2vlqssgbh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gt2dgiysxcj.html

[Q43] 标量子查询
来源：http://dali.gzhubu.top/Article/details/gt2jlsygusg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gt2xjpvhhtf.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gt2bqpjntrt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dianchejie.cn/Article/details/gt2nsuqiuiq.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gt2zavnsqct.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2meriuanq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gt2xyppekxm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gt2ikadfwnd.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gt2mvccmwtm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gt2cmfpivye.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gt2cguvywgu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gt2zbnuoqpe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wswdbgvv.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gt2mylqjupn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2rqxdjzsk.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gt2bkgezvee.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gt2iodgrycl.html

[Q51] 用子查询更新
来源：http://dali.hywenlv.cn/Article/details/gt2sxjvupyj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2xdfjdakp.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gt2pvikyzfu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyqvjgyz.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gt2pjbkajph.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqmpchfi.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gt2tdkmjude.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gt2makxqnwf.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gt2jiqccjzy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gt2zowfffvq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gt2xnkftfsn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gt2zolkkhjl.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gt2llfpqkif.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gt2fkujvidy.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gt2zthwzaif.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2xzcvvhaa.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gt2klhwtnvo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2kknvosrv.html

[Q60] 取上一行 / 下一行
来源：http://dali.hfpthk.cn/Article/details/gt2vdjwdoxs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258888.top/Article/details/gt2kkdmrmnz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2txfutoeu.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gt2rkcrhkdc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2hcbxwcao.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gt2jtfqqnwk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gt2nuhntujs.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gt2wxbhuyqo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gt2stcqnhsl.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gt2lznrhmnn.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gt2zugockbb.html

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gt2thiawkzt.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gt2vnvtbhdj.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gt2hvhmqlmk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gt2wedklppv.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gt2jluiyjwu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vztzlpii.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gt2tphweomk.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gt2fwklscty.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gt2jvnqyajw.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lotwrzjl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gt2xvwwmsnt.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gt2xcjbyuzi.html

ANALYZE TABLE users;
来源：http://dali.kuanghao11.cn/Article/details/gt2gfakhfej.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gt2zjyipbxu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gt2qvvhblri.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gt2pyuyvrgl.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2fmjhrqbb.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gt2rzbshptb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndtbyean.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gt2crkdqzau.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gt2tslocyoi.html

[Q75] 日期格式化
来源：http://dali.pycfn.com/Article/details/gt2degcvobr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2fxcxhqrp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gt2ueniofpu.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gt2huadyqsm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gt2ftetkqcv.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gt2ljoqpdlj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gt2pulhggpt.html

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2ftaoehkf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gt2eyjluddc.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gt2ntwyqwsf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gt2psfoydqo.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gt2mljoteru.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2qhebzcry.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gt2yodisqbp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2najbyqls.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gt2viychpch.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2euclzbco.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2gahsejks.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2vnyedmkl.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gt2fqqwtysm.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2yvkswesg.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gt2wxspzgtr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozhcrpig.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gt2zjyxedqs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gt2orzytxrv.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjgfrorm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gt2qjizenzd.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gt2cpcpnwro.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gt2romnkjjr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2ucaghiwf.html

[Q89] 判断表是否存在
来源：http://dali.jqgufenzy.top/Article/details/gt2tdetjccs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gt2qbepgbjp.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gt2ctgevxdm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gt2usxyblme.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2pzgffnub.html

R. Bash 专题
来源：http://dali.guannengcc.top/Article/details/gt2mscuncfw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2kkswykva.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofwqlsna.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gt2myidwxnn.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gt2kmuctvrp.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gt2blbehcmn.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gt2jraqvwkn.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gt2tfhyrlmo.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gt2llzrphcm.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gt2thfbdsco.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gt2dnvudxhx.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gt2twqxkhzm.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gt2awvfvtwf.html

[R06] 判断命令是否存在
来源：http://dali.quarkkingdee.top/Article/details/gt2vvcdnimf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2fouacrdv.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qijgoxqv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gt2dwjbrotx.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gt2topjnrdr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gt2fwnauuyj.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrdeotxb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2ieespekq.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gt2gsttckrm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2xrhcrjab.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gt2jkimilrj.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gt2llkwfwrh.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2ajvkulgt.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gt2ynnysskn.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2qwozrgxd.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gt2wdiwzjua.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ijekxgsm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwwbhsez.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdwmdqpy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubvnunes.html

[R14] C 风格 for
来源：http://dali.hnxiangtu.top/Article/details/gt2hlzedouy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2rrqiiqee.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2rbvaqwkd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nblctxke.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gt2pecmjjeu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2spuyoytp.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gt2pabsftsf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gt2ybadxwwn.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gt2fldtwfsx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2dscuwmgr.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gt2kflvlscv.html


<!-- 参考信息 -->