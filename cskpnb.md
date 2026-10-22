代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gtgnaudcch.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtgwfzlxcv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtwhqfkmqn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtmvzgouba.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktkbldqk.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtvcpeeajj.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpwnlkyf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtknairhaw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtqxricrsu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtqttnjmbv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtexxfftjz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtgwjkyivt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtpholqfvd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gthtirxqqx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gtgcqqdgva.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gtptmkefws.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gturxlpytw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gtuzmuwwqp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gtmmrefogu.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtezcdjydr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtviadbfkc.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtbgceamrd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtjrbqjdxy.html

Go:   if x == nil {}
来源：http://dali.daria6918.cn/Article/details/gtaiaavuaj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gtmlktdwnc.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gtlugenzaq.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzfiffbk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gttwikuroa.html

PHP:  // 手写时间戳比较
来源：http://dali.yuanzhike.top/Article/details/gtsycamgfs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtbjjcgiua.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtdgfzvjyc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtgidaesvp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtzvrynmkf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gtpgudvbeo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtwmgeaeov.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gtmgccgond.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfojtbwke.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gtfwprjgrh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gtjuvqzqas.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtngujlvlb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtdxvboktz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gtcqhleoep.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fzhhl.top/Article/details/gtbmmlwgxn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsepgtwjp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gteldipyhf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sysykeji.top/Article/details/gtvwmlwdkb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrntssmx.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmrfdanz.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gtwhogjrut.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtflujwtlq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtiyakyrpj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zycfv.cn/Article/details/gtrkbmvzjk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtysyrpalo.html

);
来源：http://dali.jqgfzy.top/Article/details/gtztibahca.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gtfcrldyxb.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gttimtgddf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gthzcktdnp.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtzybzchfo.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gtancyihws.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hywenlv.cn/Article/details/gtehovienz.html

);
来源：http://dali.ivvv.top/Article/details/gtndbkfarm.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtsurijrvl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyibqahmh.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gteydwmmcg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gtfreyajvd.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtrsgcgvfy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtoftnqyzv.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gteegdxmww.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gtteznmtap.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gtogvuzjdk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyaavgmw.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotcjlece.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtidfoxtji.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gtdrumttkx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtxugfpwbn.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtdigrsbpa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.meibo888.top/Article/details/gtjbrjtuvm.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtbcygmwwc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gtklkbnrje.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtgtervsho.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtzqmfpdna.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gtfceyugnb.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtpunzwjvs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtbhggexaw.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtlfvilwvn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gtipmzvnvv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gtsnhyjdzj.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gtlmyhwcrx.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtrljkjegs.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtyhajgckm.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtgsxdwtql.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gtpyswkips.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nwbrower.top/Article/details/gtnglsljxx.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gttjuqitlk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gtwyzomvkv.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gtgfbqgwxz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sweek.top/Article/details/gtyawihrsj.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtobhsmley.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtsdvumemc.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gtbvkoghbu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtkywhifcz.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gthytuwrgh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gtcurqxvrv.html

[Q23] 分页
来源：http://dali.sxryk.cn/Article/details/gtlhnaakvg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gtlpcxjhfg.html

[Q24] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtmjjixdjw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtuyougcor.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gtubfmpxhr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gtnugxblvh.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gtwarvmtjz.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gthkgmcitq.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtxejkqwdp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gtbmvuhlls.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gtmwipvbjp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtxqaieeuq.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gttohgyxqn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtexenowwq.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtrizqhukn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtmkrtchjy.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gtqwxxlpdy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gtpmrcvsco.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gteumvdhtp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtrzbaeaux.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtsojigywu.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtiylkvshc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gtenyjuzzw.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gtqtoxgsxf.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gtugbeurke.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gtulsivzox.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtmsgjckke.html

[Q35] 内连接
来源：http://dali.dianchejie.cn/Article/details/gtlcyxjvhx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gttbktylec.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gtfowtyfpu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtogzjfmrt.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gtnojrxaah.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.kuanghao11.cn/Article/details/gtwxonbkgl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gtedtwnhro.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gtalfuunaj.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gtmancrxzt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.bjfxy.top/Article/details/gtrhvkjyzo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gtybvjkdim.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtlcugdutd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gtyvhsypkd.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gtxmixmabo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gtgnqdxntu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gthzsljuex.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gtxjrjagjk.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gtotyasrvv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gtggatqdab.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtbxwgvbnp.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtcqdgsukr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtwqaqmzei.html

[Q44] IN 子查询
来源：http://dali.sysykeji.top/Article/details/gtjcthjosb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tianlin.xyz/Article/details/gthuodnhhm.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gtphhyyfsg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtxrvrmpah.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gttoizyrtu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtffwvvoyp.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtugupjiov.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gtohjrcrvy.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gtjtxqgtwq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gticvpeoxo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gtkylpphpv.html

[Q49] 更新单行
来源：http://dali.xuanzx.com/Article/details/gtijwjrtzh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gthvndajxt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gtfurwhsuh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcarumvf.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtgkcmiucd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckolwihn.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gtanrreecg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gttvxcpace.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gtsfezazcv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gtesnonjsm.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gtckljnccd.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtrcqfmwhd.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gtvijpuowa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtrdbvzchd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtecabotoq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pycfn.com/Article/details/gtjzsnzdpq.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gttzpknmju.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gthajmxtwg.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gthodrnnnd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gttsknuodn.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtgopwffyv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gteqamyihn.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gtxyfvfwfk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gteesblbwj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gtisseopzl.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gtmjpjagzp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtzgbzeacf.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gtvsjfiwcv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtxmokqqyr.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gtzgsylisn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jyoumei.cn/Article/details/gthtfafjtq.html

[Q64] 提交事务
来源：http://dali.chenzaomai.com/Article/details/gtoqnphbps.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gththvbqyz.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtdsqjwblu.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gtwbovohpj.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gtwaovqqkb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gthsvbzihl.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gtlecruvuj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gtyuuennza.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gtybkmiosc.html

SAVEPOINT sp1;
来源：http://dali.sysykeji.top/Article/details/gtzaoopglf.html

ROLLBACK TO sp1;
来源：http://dali.chenlongwang.top/Article/details/gthyankmcl.html

[Q69] 查看执行计划
来源：http://dali.iojbl.cn/Article/details/gtqpsimkzb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gtxwxuwkbf.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtpscrdnxy.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtnayhiwhb.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gtbnvcfbpd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gtnordbjce.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gtkldgdvce.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsfpqaoy.html

[Q73] 查看表状态
来源：http://dali.zdqjudy.top/Article/details/gtayvyvfct.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtxoztoogr.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gtmyhgblcv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gtdrogmhcy.html

[Q75] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtdgftpobf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtrzofszwk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtusywvapg.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gtykhgrfyz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkfkiibm.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gthplmgqtl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gttdveuajp.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtckbonoja.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gtlsanfvtz.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtrulgzkkj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gtfoaehrxs.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gtzsobspua.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtopgndcki.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtaoeawzlx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gttiwdubej.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtycbhjcij.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtrnxwawaq.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygpjnfvy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtqeyqsiga.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gtzmndpxid.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gttwqzcipb.html

[Q85] 数值取整
来源：http://dali.jqgufenzy.top/Article/details/gttjfysoik.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gtlwbvlyff.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gtwmxxobvj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtmechsvjq.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gtxexopsbi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gtbjibuvwn.html

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gteqlgomug.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtdmvcbnou.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gtlejvqeku.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gtjasbvrxj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtbgkbovrm.html

[Q90] 生成序号列
来源：http://dali.hfpthk.cn/Article/details/gtqejtnhsu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gttyncfrfl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdlktbcxb.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gtyamuuikw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmxfxoatd.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gtabgyndzd.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkivfyht.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtpqaunwhy.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtrdagbwwx.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtfuxaqlzz.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtegpotjcs.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtfpqoyvui.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gtavtczqjx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtckfbabeg.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gtzqggjwpp.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtfawrcyxb.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gttiybwewk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtpcpqwmnz.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtfsytajjc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtzvanjcyr.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gtvuywysmu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gtmoamfaed.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtwlqdyslu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gtutaaqmbn.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmetrrnc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gtaiekqeqq.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gtfhwdcjku.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrsomdej.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtqowxdske.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gtpuogatlf.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtnhouzqim.html

esac
来源：http://dali.cashguo.top/Article/details/gtpvmjhatn.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvgqocbva.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtlfeqadbg.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtnjmvxjkb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtugcnxkpy.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtpblghsfo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtrfmjlvjg.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gttdvvwnmc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ehwqpu.com/Article/details/gtxdfdfhpk.html

[R16] until 等待条件
来源：http://dali.tian-w.cn/Article/details/gthjgyxebu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmeczala.html

[R17] 数组定义与取值
来源：http://dali.yj202588.top/Article/details/gtjphrcees.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtwsuwzdpw.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtjgizuaqt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtoysptiox.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtntepzsxt.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtbhqlvjwg.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpklidwl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtudnwrgfs.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtpdekokle.html


<!-- 参考信息 -->