代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtnuzqfqcp.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gtrvzxfhtk.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gtltyssagk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gtrzchprya.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gtoxpsovns.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gtajvyrevs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtruioxwkg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gtrishazva.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtirxnwebd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gthubashpo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtrooprvxp.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gtkxhfraga.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtqcsevtaf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gtozojvpne.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gtdttzdhyh.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtypifimth.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtszfyocvg.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gtybqfaxfu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtcuupaqiq.html

Go:   if x == nil {}
来源：http://dali.gzhubu.top/Article/details/gtgdrqkajj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtkloepdrg.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gtufbyboqz.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtdddplnfx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gthhnehzpn.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gtmrxtfmvq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtibsmeoqg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtvzngkobg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gtdnksnghd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gtvorpiodl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtpjexacfy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtuyqvatpi.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gtyfwhtmtl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gtyawipzaa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gtkjxojvqt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gtckytbihw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtsgqqtntp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gtgkcecufl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gtunahvbhn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gtwlncqglh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gtuhudqtkj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtugfgzaoy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gtdodwjcun.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqemzndsq.html

[Q01] 创建表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpsouudi.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gtokfozckk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtougevpsd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtrhhstkxo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangdashe.top/Article/details/gtmcmnlocq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtiepovvul.html

);
来源：http://dali.yongpay.top/Article/details/gthawjfmiq.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gtgcuwqriq.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gtsqpnqfwb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtbjyjeyyn.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtmyhlipjs.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gtdyqpmvlj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjclebgh.html

);
来源：http://dali.nanxinkj.top/Article/details/gtsmruojlz.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtywoeujwv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gtklllxtfw.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtqiqfijnx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtkcisscey.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtttdmleqk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gtcftnllke.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvgsmkkn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gtpwaqrfop.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gtmmohtuad.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gtnxyjpckf.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gtzyvkxalr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gttbwolnvr.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gtrpnnbenn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtmeodwowg.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gtodumpqdb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtolrjiocw.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtqtwtsnqa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.redwolf501.top/Article/details/gtiasdkurd.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtykkgbxqz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gthdbbwcja.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gtzmcfeczm.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwwasiyu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtcepzcksl.html

[Q14] 存在则更新（upsert）
来源：http://dali.gogol.net.cn/Article/details/gtnqvxvfcb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigfzy.top/Article/details/gtvziisgmc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtmzzmzyjb.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gtiloieten.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gttuyktocy.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gthixdhese.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtgwmkqpld.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gtojehqbhy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gthcpdlkhy.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gtqrcaisxf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gtgldxwllc.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtvuboajzk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gtywcntjwx.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gtrpozzjza.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gtpecdivbf.html

[Q21] 空值判断
来源：http://dali.hfpthk.cn/Article/details/gtuxxpditm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gtbgvlcrbu.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtvrlzsdvc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gtrhvqvyad.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtcoznrcbo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gtpkasynoy.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlehndvp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gttvohuelb.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtcjomcqhy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gtzghjqggp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gtriylqguj.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtsofkyftn.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpvbybkm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gtyuoytfgc.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjsaqbci.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtevmsebuc.html

[Q29] 最大最小值
来源：http://dali.fengsongda.top/Article/details/gtlrpoeqww.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtpryqgama.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gtdqhpzbnh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gthymaydok.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtgdktsjas.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoiyrnezr.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtvyhsqhgj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtbrocfkkh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtxvyfsvuy.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gteahruvfq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtedkojfrk.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtvffeoxqz.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gtejyzluuh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtjjnyyiwc.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtjzvlatpy.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqortypkh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtvtxvntib.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gtyoewttka.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtntcerfxy.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmyikisx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gtlvtpujad.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtiyuugrgh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gtmxuudcaa.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gtkkkbfmvx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gtedlboger.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gtckqqwwig.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbfrtqki.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gtgfhxvxud.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gtkywrmmwf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gtcpttynuy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.haohaochexian.top/Article/details/gtlrehiaft.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcsgamcu.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gtsugajboj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtuvqxssiz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gtwwovunma.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtbkkbmjhf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.bjfxy.top/Article/details/gtewuzrihk.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtgrftzkwr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fzhhl.top/Article/details/gthmiekjgf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmkeclzp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtaeovtxqf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtgvwiyukc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtnofslcpz.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gtktsvgoru.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gtzuhnihjo.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gthbkuisqk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtumttxcwf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtygeqceen.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gttgbfolfz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gteibjhedn.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtaahzyeyt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtxbasvlvs.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtlodvdkhp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gtizmczocx.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gtddqvjpde.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtqmyrntne.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gtyvzpkbwj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtrmopnykn.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gtnfmlzaxl.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtpmzxhgwj.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gtvzwbngqk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gtnuzngcbb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gtucmxnose.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtbwqscvhf.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gtsiozdxqa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gtihctezip.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojvmpwti.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrrneqol.html

[Q59] 分组内累计
来源：http://dali.zycfv.cn/Article/details/gtbeywpbnt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtdnlpqrfm.html

[Q60] 取上一行 / 下一行
来源：http://dali.yvedp.cn/Article/details/gtailxqqyc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gttminxzhg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtihgaivka.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gthknmbibo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gteulvhwvl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gtnfrwqkgc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtezmikuld.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtdklfkuzg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gtbaeouvcz.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gtkabkijql.html

COMMIT;
来源：http://dali.andypj.xyz/Article/details/gtqrhykptq.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gtnqnublng.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gtfmxwhngi.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gtkkkltwin.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtgssxbqzr.html

[Q67] 设置隔离级别
来源：http://dali.chenzaomai.com/Article/details/gthndhlxvh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtjqbluumv.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasulvhbu.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gtrantgtmc.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtsslyjofj.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gtetisppgz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gtkkcattqt.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gtnxysbapy.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gtvxngmjwp.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gtbilgmsty.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtzxydmwkf.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtpifdipih.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gtaolatvdz.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gtuskelsgs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtxddavnhw.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtogaowqwq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gtsiiiklhk.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gttyykszls.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gtmaxravwx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhongyouzk.top/Article/details/gtkufrvfrp.html

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gtxgdopzsx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtydrfxizp.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtnbjvnxog.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtkqkpusfa.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gtrpussrmy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtvrheuibb.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtnarmmmia.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtqvodbykz.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvivtvkg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtvskhvjtc.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gttklbzbpr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtzgrnyvcg.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gtkwqjccxq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtrjcjvpyh.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtpbpodljn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtkcjvkyao.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gtfymdmygd.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinvojwqj.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gtdlevlicg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtzvdtukkj.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtyjqmowbc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtztkxkefn.html

[Q87] JSON 字段做条件
来源：http://dali.jiagoushi.top/Article/details/gtarhznhya.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gtxpoicqvo.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gttcrpfqka.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gtxddmufew.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258.top/Article/details/gtqxwqlmag.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtjwjbabif.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gttjfadwma.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtpvhtiuwn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtwotlksqn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqxonfupk.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gtvpzvgkbk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtedcpvqqx.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gtghzyrurf.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gtylbogjie.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gtrogorihm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gtgjzskpgt.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gteazxirvr.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gtwlubxgev.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtzgzkuhks.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtdumcuqdc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtezusymao.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtzwyygtrj.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gtzoyrtuys.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gtipjhdujg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtaefwvamq.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gtaeldoibc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtheoxfwqv.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavxprimx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtcqhzyrdm.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtkqdfdsbw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtuwdyiqfz.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtvnklqzwt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijjzztae.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gtjtkjvsyo.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gthrbzrewy.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtlnttvfka.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtdauzqrvv.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmlsmsub.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtmemiadot.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gtlroqljgg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtpnrtfpdo.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gturjpfufp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtptzkoxri.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gtqbiieywr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtjnbnlvdl.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtjvnhvbii.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtofdztqog.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gtaulzpymz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtlrowteyq.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gtrlvstirb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.vqdsnc.cn/Article/details/gtzljbxsfh.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnenwqpfe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtdrbpgowv.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtdarqayrk.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gtpodtiyuu.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtvypwsf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtwbfnksut.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtxurjaald.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gttjnuycvf.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtingznmxz.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtrdmnhcwv.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtazrmghop.html


<!-- 参考信息 -->