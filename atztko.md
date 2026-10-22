代发 wailian999

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtzdfgceyo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gtnjlosqlq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gtrynfnddz.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtdvtewnrj.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtsnjrcrfy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtyslcsjox.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhoulong.xyz/Article/details/gthmibeasl.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gthgoejbww.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gtrausbxnn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthmkiyxkg.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gtzltzgfcc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxxfxhwxy.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtwdikbgts.html

Py:   str(uuid.uuid4())
来源：http://dali.316326.xyz/Article/details/gtqfcrjnou.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtclquqtlo.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtosnrishm.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtnrxvpuxf.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gtkrxsrwto.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gtpofstsfb.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtktdncjez.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gtvlcdwmfx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtlibjyjpa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gtzhgdccbm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gtvgqddyej.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gtxgszlbsh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gtjvzsrqxm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlauxqici.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gtninqitqm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gtxgejbcvz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtytiyiihf.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtrakljics.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hammf.cn/Article/details/gtylelzulj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ehwqpu.com/Article/details/gtbukfvapt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtbgbjgznz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtwhtmzcao.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtdxtmnphp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqxyflxx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gtwxkicetf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gtlvvkptjd.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gtaqkhrnib.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gtfttlpwyj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtfkpzlptp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtcbegabst.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtwlqrjvux.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtdhgqrcrd.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtnvrjcmjq.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gtrkhwxmwd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gttmoxbgag.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtainegclm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gtfuamifrm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gtseltfynh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gtbufaqvvs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gttvslzbix.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gtrgtawfqg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgfitips.html

Ruby: a == b
来源：http://dali.hnxiangtu.top/Article/details/gtuoqvgxmn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkifwdmy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gtafumsrbx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtkjmtmncd.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtxrjtvhbb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gtndrrwraq.html

TS:   if (x == null) {}
来源：http://dali.cheryme.top/Article/details/gtortglsfd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtnxvaheos.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcmjlqkjn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gtltdwimbv.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzcdjogq.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gtorbaicun.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gtfjierunj.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtauzyludf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gttbzfwcfe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtdugiqsik.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gtqcxzgeka.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtvagkjgyz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gtbejjlpyc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gtjjrachom.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtdfdecrcr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gtiqfdnwrf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gtgudbfgmz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gtuavgpfxe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtpthyayzm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gttixkdxqb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gtgrwvthui.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gtgyhuwseb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gtaxzxtgun.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpdqsvapu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gtzxxvmhzz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgedwcxhz.html

[Q01] 创建表
来源：http://dali.jlsjyb.cn/Article/details/gtvijqqczy.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gtfondqxhh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtucdiibuu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtozoowxkl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuetiantiany.cn/Article/details/gtfhereppp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gtbqrdgywh.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gthupxkqdt.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gtppykjnmg.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gthuxqnwzr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtxwbgfffq.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtwcrudkdl.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gtbzqhfriy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxztpvjfh.html

);
来源：http://dali.iojbl.cn/Article/details/gtxzssbxbc.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtlpkyauxo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtjxohbqrq.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gtkzlsambb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtzrizfqey.html

[Q05] 重命名列
来源：http://dali.hnqzz.top/Article/details/gtuapummrg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tianlin.xyz/Article/details/gtqlhfsgiy.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gtcxcpamaw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gtqllkljix.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtwtanofiq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gtdpfvncmr.html

[Q08] 创建普通索引
来源：http://dali.shzxlz.cn/Article/details/gtdbdkvnlr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtjqrysaxr.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyabrtuj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtpynmfhdo.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gthgdgwnsv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtxdngybwi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gtvpxubtlk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtjgnxarhq.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gtjmpbvseb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gtgqpdwipt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangshuangyany.cn/Article/details/gthamkdzug.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gtelfgtwvr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gtvrpvflaj.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtggxafdbr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrkyorex.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtjfqwautx.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gtptzfmarc.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtyybspxko.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gtvhgupupm.html

SELECT id, name FROM users;
来源：http://dali.cheryme.top/Article/details/gtsaoczwnl.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtaalfzhyl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtqkvwsoxf.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtnxykakof.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtmwfnuxua.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtldkznumm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gtgmjxwitv.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtxniifrnx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gttpliiefd.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gtxdhvhjih.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gticdbovsb.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytmbgrge.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gtzyqgqjdi.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtfsraxbay.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gtjopidoth.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtiwbgzljs.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtdyxpwvju.html

[Q25] 只取前 N 条
来源：http://dali.zhengqikj.top/Article/details/gttgkmmxic.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtmtzcwxhp.html

[Q26] 计数
来源：http://dali.yanxiufei.cn/Article/details/gtldjuugef.html

SELECT COUNT(*) FROM users;
来源：http://dali.sysykeji.top/Article/details/gteitucvqi.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gthphgkjrq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtqenqnuru.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtoqpjrvxm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtqeudhiqe.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gtxpjsliab.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gtxfhabers.html

[Q30] 分组统计
来源：http://dali.nanxuanxn.top/Article/details/gtyyyfwnmp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtandwhdsv.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gtrramrptx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gtpllqtonq.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtakcxivcp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtbrgpalhj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtlafahjzw.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gtccgvtgxa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gtnaxuikdm.html

[Q34] 每组取第一条
来源：http://dali.zhixingplan.top/Article/details/gtbcdrmdbd.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gtsttaozrh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gtaajaqjet.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtcppicntx.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtxzzrjbfp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gttlcwscbb.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtndihnyxv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtxrnqnhnb.html

[Q37] 右连接
来源：http://dali.xuanzx.com/Article/details/gtqzxdlrxr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfryegtal.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtbqhihjwi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gtetayecyd.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigufen.top/Article/details/gttpnywies.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtgiviscej.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hfpthk.cn/Article/details/gtyfvbskqc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gtxqjaxpej.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gtzihwcfdu.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gtsvfnzehz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtmagqndid.html

JOIN users u ON u.id = o.user_id
来源：http://dali.redwolf501.top/Article/details/gtdextfnqy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gtyjuhwpaw.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gtawuugqnh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gtpxpqahda.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gtgopiceuz.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtapogozfg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gttsodxwhr.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtatndmmad.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gtgmwzmzmh.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gthuuluxrx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhxfkeku.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkaoaoljk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtcmtcudjj.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gtcyujruwf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gtmtiuqgsc.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gthzkdmypu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gtxctnikdw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gtdrbkluai.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gtjjuojyqk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtqvjadnmt.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gtwsmqvqly.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtyhgdutkg.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gtvkzgjyfq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258888.top/Article/details/gtljamxxpm.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gtmvemille.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtrkuwywln.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtqrocjuqz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gthqxnutyk.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gtyakoesla.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gtvoxwydgv.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gteeumqcws.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gtqobrpvdf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gtycxbjiic.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gttlqmfmed.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gtyeyaqpot.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gtdanwndwr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gtghharmci.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtpeuevgrz.html

[Q59] 分组内累计
来源：http://dali.zycfv.cn/Article/details/gtawgbvqnx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtaljusxfo.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gtxoaxoxvx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gtkkcxqklv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtkcltbqlu.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gtumxnifyu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtuglscech.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gtavcnqjng.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtijaqspgj.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtiduvezqk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gogol.net.cn/Article/details/gthhkhkvqb.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtvubojvsj.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gtsipsbpdx.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gtuofnpsyf.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gtdrfihlfx.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gthbshropx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gttbcatllm.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gtezpscgkw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtfpjfniyb.html

[Q68] 保存点
来源：http://dali.tian-w.cn/Article/details/gtxehkuzsf.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtymvobouk.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtmoawshkx.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gtktgcrpaz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtktgpthgm.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gtsplknehw.html

ANALYZE TABLE users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezrtiooa.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gtzcstklvj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gtbrrzfemw.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtqsmpikyz.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gtznrltoiv.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gtincjxqsm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtlghzyoql.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gtifmyzrph.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gtktahsmqe.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtoahhorwp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gttchezxpk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtvlndujwo.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtwcexeznv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shzxlz.cn/Article/details/gtfbiixtmy.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gtyvfxqejk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gtqwqmtfty.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gttzrjaejk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gtocueyoyb.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtqoehunag.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gtqzjezcav.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguixfbzc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtetacxnto.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gttufmbmxv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtkdfzkzrc.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gtrbmmzuxo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtnitxvxdc.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtzjodvlrl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtjazzwimz.html

[Q84] 去除首尾空格
来源：http://dali.vqdsnc.cn/Article/details/gtlktbdccy.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtwigraywy.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gtyhsmbpgn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuefcsmlf.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gtbygilzcz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhbscdhc.html

[Q87] JSON 字段做条件
来源：http://dali.ehwqpu.com/Article/details/gtnjqtppev.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gtbmheiqon.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtctwkbgkl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtizptxwsv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gtktfdxcvm.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gtinepgire.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtboolbwwe.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gtoetkbjxx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gtfuupjlkh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtykdwxaby.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gtcwlmfhfy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrtzyzklm.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gtfxzhqqan.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gtavoejjqd.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtjweeyvdy.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gtfifjnhaw.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtyrcsrksl.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtgbzviwls.html


<!-- 参考信息 -->