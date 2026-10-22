代发 wailian999

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtykkhjbuz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gttqvgkfqz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtoicmmhyw.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdkrowet.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtismwurit.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtkiohsthg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtixkktsba.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gtizhjwrsa.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gtlxqyjivb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gttzswldtu.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gtmibwszlj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfpynmexq.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtrpicaeyt.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gtiehltpfk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gtiqrxopym.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtmhsjhnmy.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtzqreknfk.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtwnpjvpgb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtogtcwduc.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtzriyywmy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtkqpxeewg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gthpppyvhe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgufenzy.top/Article/details/gtohxizmkn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtlqyjnzix.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtbvvzvgjp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gtsqqltdpr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtabtskagl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gtbqrwrhow.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gtqulyczcf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gtfoknetui.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gtowjiecjd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gtbklqdkwd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gtnmallkur.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwdeiper.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtioyhtqgl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtmbxefgte.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtbztylyok.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctrduvbv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gotoacloud.top/Article/details/gtecgyhfpn.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gtyyhfxsar.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gtddrojion.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtydbsnlet.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtoievyjbu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtidosrihb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxjomnvm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gtuvtqgzss.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gtplekaamu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gtlqxoxmhr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gtukrylppk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gtecxgltwr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gthxqytesl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gtrrovenvo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtrezhysxm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtgvwedqwf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gtldaesfpb.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gtgqwjenzt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.havefunace.top/Article/details/gtpqvbzpwq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gtilaodqah.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gtjymrgsnj.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtavzmgmlc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gtsvgonwyu.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtoimmwnks.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtglynnxxk.html

Go:   if x == nil {}
来源：http://dali.gzhubu.top/Article/details/gtqsxrhayu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gtqyhjykhy.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gtitzwjhan.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtoulworvq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gtsdmsxdjx.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gtpxnxetvt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtsoccgtwu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtskverrbp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gtjzccogrl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gtwjedeyrj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtkdzfoptu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkizfyaia.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gtmwscqgnq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gtqakaxuuo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtvgfqnjxq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtklkdoxjm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtbrwpgtix.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtoxdhkbnv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hysaishi.cn/Article/details/gtijgroulk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gtvvwmeiaq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgiqjypeb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqzqjqiqg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tianlin.xyz/Article/details/gtiiuemcan.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtnnuiwide.html

[Q01] 创建表
来源：http://dali.316326.xyz/Article/details/gtxkdaliyi.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtzbpvntft.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtlselhija.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtrtenbatu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtpfucckeq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gtwhnbhmef.html

);
来源：http://dali.tian-w.cn/Article/details/gtkhaamkfn.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gtuddpntvh.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtagyhkjxd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtvvqkrrjh.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtcashespa.html

amount DECIMAL(10, 2),
来源：http://dali.daxiang520.top/Article/details/gtqrvsdrsg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtqkfcsqtb.html

);
来源：http://dali.snrcjt.cn/Article/details/gtsjxnxink.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtfyudhxks.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtmiaoghdh.html

[Q04] 修改列类型
来源：http://dali.nanxinkj.top/Article/details/gtginomhfx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shzxlz.cn/Article/details/gtyejmbukz.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtuebbwbgn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtirdkxfge.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gtmbtczvhe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtgqdsukmr.html

[Q07] 删除表
来源：http://dali.yuxming.cn/Article/details/gtkvwotjio.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gtcxnjirxg.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gtdcugpmyq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtsnayipsl.html

[Q09] 创建唯一索引
来源：http://dali.0kj1m.cn/Article/details/gtokqnxjld.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gtfsklfnvm.html

[Q10] 插入单行
来源：http://dali.guannengcc.top/Article/details/gtyrfhfuxb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtcdoaayfv.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gtqttewzkf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.redwolf501.top/Article/details/gtcbjhdbfz.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gtsultpqre.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gtvtoxkizy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gtivpjmfxj.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtxpzeript.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtunrasgwy.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gtbyxtmrxi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtsaumjmrs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gtshbrrpqb.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtpmvvqxqz.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtpnshnvve.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieflonbp.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtfkrjfhqc.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtbcqesqvy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gtxnlzjelj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtebvdpzwu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gtbfoyzeon.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtpssroaap.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ppjwa.cn/Article/details/gtcuuwmdsf.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gtedjncxsj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gtxdhnhzon.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtahrbyooe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gtgzfsgrws.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gtxiutaigf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shzxlz.cn/Article/details/gtbunhhotx.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpamvzkjq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdksxveoo.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtsydwwjhu.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtxfqmkppl.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gtkxdjozwb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gteakwctlz.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gtizhcrimw.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtvbjdsnav.html

[Q27] 条件计数
来源：http://dali.guannengcc.top/Article/details/gtzbnpjafi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtpjnuguiy.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtgbxgzgke.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtruiefiqt.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtjpbdvnwn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtzyajvfdh.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtyrpvzvuy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtuljyrxck.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtavhjbqlx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtyxnxewjh.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtgekkdljc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtlmoorzod.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gtpoixgwac.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzbleiji.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gtkzrfhkvw.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnulwonnn.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gtlytnoyeo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtujvcqfwb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gttpvvdnnw.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gtutdbhewu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gthwunnznu.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gtlfwwkovc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtyciuxpfj.html

[Q37] 右连接
来源：http://dali.hammf.cn/Article/details/gtonvpjrwn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtbbpafmgv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtgmraygaw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gtmsolptut.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gtyotztdya.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hysaishi.cn/Article/details/gtznbjkcfr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gttmjpayhm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtxeqlikdg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtxjtvvthi.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gtiqixohds.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.iojbl.cn/Article/details/gtbuxloedy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gtnmdctfqj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtyseimgge.html

[Q42] 连接条件附加过滤
来源：http://dali.cqqwz.cn/Article/details/gtpkbwuvln.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gtahudfmdp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfpilrbu.html

[Q43] 标量子查询
来源：http://dali.zhoulong.xyz/Article/details/gthoicxgvh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtgwkuaexu.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtygkrszvf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gtveyywqfz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtncvljclb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtdjszolys.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gttwoohjon.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtxcmlswzv.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtfrpyptxa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtxdygwiju.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gtcahltwqy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gtdcmevldt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtzmthrfjp.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gthetqmlye.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtctnewtqu.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtrigdmwyb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtoddsklhi.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gtywfktptj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gtnkpwidbz.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtygmccbsf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtycjqhmlq.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gtbdpvghlb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtknchexjy.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gtijigfeeq.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gtfrwtopej.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtbeuxgdok.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtjrbvffae.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gtlyprpzqs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtfnyyqgxr.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gtokcrqagk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtsxauuokq.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkahtluc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtmugkcynm.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gtpzpobfsw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtovpqcwyo.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gttholwftc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gtkbstsupm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtmkzxfpbo.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gttdkyohux.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtrmqhgkfb.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gtovoyfprc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtxdgdryxw.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gtugyehauj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenjidiqi.icu/Article/details/gtlefjoyzm.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtkzdujwsc.html

COMMIT;
来源：http://dali.ehwqpu.com/Article/details/gtcsxggers.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtnaeduznz.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gtavvcpoqp.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gtncqxmbwr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangshuangyany.cn/Article/details/gtlhfbdmmb.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gtklnfsvll.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gtlujpcbzh.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gtvrbnxxwi.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gtygbrzbed.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gtscfcpovq.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtilgogpcq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gteldkrueg.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gtnohdopdr.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtkqallesu.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtgnzdwvmi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtlwwcopgr.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gtjjybnoin.html

SHOW INDEX FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtdvlzawwz.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtkayhejpn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gtlttlgkkc.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtfxzvzlid.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gtkufctjff.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwhjnqtp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtepnyfcri.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gtuboetiie.html

[Q76] 按天统计
来源：http://dali.hnxiangtu.top/Article/details/gthmhyabts.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtfgcolish.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gtvbpyiqdg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtngfssqjd.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtjjiznljw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gtgwoefpto.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gturlmltet.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gtlftzybgu.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gtynnoofsj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gttcxkceer.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtakbjhnpr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gtjkyjyztk.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gtlosmdcvh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gthgjrdzbc.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtpsldwmcz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtnozjtyxx.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gtupgefsvv.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtwfkwxyui.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gtribibans.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gtciwnknlx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtdenmjwmj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gtfzedzbre.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gttdmomqoc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.vqdsnc.cn/Article/details/gtflfyalgi.html

[Q88] 行转列（条件聚合）
来源：http://dali.ehwqpu.com/Article/details/gtjdikakzz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.bjfxy.top/Article/details/gtdovabkmy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtdoszohds.html

[Q89] 判断表是否存在
来源：http://dali.hfpthk.cn/Article/details/gtvbtrxzyu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtstuntqkn.html

[Q90] 生成序号列
来源：http://dali.tianlin.xyz/Article/details/gtzxjuswqc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gtafmqrjkn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtbzcoheax.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gttehgjymd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxjwizbua.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gtvymhpnxu.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gttwhohmuk.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gtjqwflure.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gtmzqdtuqg.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtmlehntpt.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtabrywocf.html


<!-- 参考信息 -->