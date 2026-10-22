代发 wailian999

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtemmteeuo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzthitrda.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gtndofiozd.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjuxwdjt.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtohcoqwze.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gtggipagpr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnrujqjx.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtbalrqpvm.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gtdccrpwnw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdubilxxv.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtlnnsxajy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjeespxew.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtzxqvjarc.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtqomnobne.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gtogvannue.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtuvfeccoc.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtihkbkpfv.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gtrkrmfwdh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gtfpofwxmm.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gtomitbwnk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gtahyrurru.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gthtltrbfe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gtlxvmzsql.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gtpksvztba.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtztseutte.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtlxjehvce.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtlactjcds.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtxpvnllaj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtqphogiro.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtwdqnhoub.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gtamfwupqx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aizwys.cn/Article/details/gtphihjxck.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenjidiqi.icu/Article/details/gtspzdazwn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtnxnrhpfm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtsahvtekv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtrkdyrnpp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gtfyqjgljj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjztcdmie.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gthqbeuozy.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gtbhqkowiw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gtszoasbbo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gthvvspgty.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gteakpeicm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtjreaeojy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtnfuarovs.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gthicqhblb.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gtdbwncwgw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tanke756.top/Article/details/gtvexjvnuz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gtivenxixc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtodnvesvo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtzdwimckg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gtufmhcooj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtfplirobg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gtstmctcmz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtsyrmqbqa.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gtxgdlgocr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gtnshawtug.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dianchejie.cn/Article/details/gtzpqohjdq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gtdksfrhcy.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtqeqaducd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jyoumei.cn/Article/details/gtgushemcm.html

TS:   if (x == null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgwrcwjgw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawsnffsg.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gtiifxiiky.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sufxvd.cn/Article/details/gticcwztof.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gthswigvpj.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gttgszxvzo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtinmdskcs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gtlnosjjwo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtchzthcml.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtgqjhijkb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtbnkceune.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gtocznonle.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gtxksaodos.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtkohhzzsb.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gtnqloijyl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtklehtrpt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtnhqgxoyv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmbertak.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtcmwweirj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gtlhqwaani.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtrkynclgq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtqzjntxiv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gtuhfoyzit.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtteuevkdb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gtoxnvyhrz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzdzkqmug.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gtswujmsvv.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gtiiprurkd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtflsivchs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtsfdzyvrk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gtbefnycoo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gthpkzzpiq.html

);
来源：http://dali.hysaishi.cn/Article/details/gtqkpmszzq.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtueyslogq.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gtbzgkproz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtrvrvlcsj.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtqqezcevi.html

amount DECIMAL(10, 2),
来源：http://dali.andypj.xyz/Article/details/gtvhnulhmr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gtdogrhbeq.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwostutpx.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gteoartrnp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtnxgylfbe.html

[Q04] 修改列类型
来源：http://dali.smart0.xyz/Article/details/gtvkjlvpmb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gtyyjweqlm.html

[Q05] 重命名列
来源：http://dali.cheryme.top/Article/details/gtqscgrxiu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gtpgdlddvu.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gtfcigvvis.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gtifbpngll.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gtxidkwevv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtcpearvbr.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gtbkrudnyi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtzkdzenco.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgphoxmq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtqwbvqtof.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtpkcsecma.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtuujyuggz.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtmebizgrn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtmhhffmsh.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtgoiggpbd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gttndvxgbn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gtvvienyci.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gtyrdcyrbq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gtcrleudoq.html

[Q14] 存在则更新（upsert）
来源：http://dali.tianlin.xyz/Article/details/gtbafsgpgn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtuspmmzaw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gtwzulnmtz.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtyxoafamm.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtssrufgao.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtaehmbohv.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gtriqykbod.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gtwxlmfznp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtvdgrohwt.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtxvadvlic.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakfbnmuq.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtwvprocli.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.vqdsnc.cn/Article/details/gtrhbhfvil.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gtkkmcglzc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gtmvdzttwn.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gtqnvzhszl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cucudq.cn/Article/details/gtlztyazwd.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gtxkabdsqy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gtafuuzblc.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gtsnmqaolg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gogol.net.cn/Article/details/gtphwdwboy.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gtgkbjybkz.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtnppvaxzp.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtvupnpwqz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gtnvrqvsad.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gtvelwvovp.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtbroqthkd.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gtpleuxfor.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ivvv.top/Article/details/gtnitrkcoz.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gtthigygwc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtsozhwuxu.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gttjimnkyz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtnavamfhs.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gtrnametgq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtuxkibutp.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gtevsccnhz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtzndlutnb.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtztdfnrbo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gthqmjlbgi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gtnvtmdomw.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gtefmgdhvm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gtguxosxon.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gtbwiuqkor.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gthasopryv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gtpapaopfu.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtcbteuwgk.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtmsgytats.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gthljyslta.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtzlrtswgh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtlagicjbk.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtdkwwugtj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zdqjudy.top/Article/details/gtihzsynon.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gtekhyxzke.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtbejsyepp.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhjvrmuy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gtythcwuyz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shuidangran.top/Article/details/gtvuonvmat.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tianlin.xyz/Article/details/gtezmcohlr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258888.top/Article/details/gtounpbhhn.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtaryxcqwr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gtaihxmlfg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtxplupiur.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.snrcjt.cn/Article/details/gtacoyqyoh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gtjeiwjnop.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gtmpzrbqds.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yvedp.cn/Article/details/gtzvzcpnir.html

[Q43] 标量子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlccvplu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gthnykfbvx.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gtoortlbmb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtbqynergw.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gtopbryqgt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtcnjtvuzw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gtsoqdvttx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gthzfwzpzb.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gtlktbhhzk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtrmbiyheu.html

[Q48] CTE 公用表表达式
来源：http://dali.gotoacloud.top/Article/details/gtztbcvqfx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gtubxawbyc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gtynzpbiht.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gtlkxhbcct.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtsukstiji.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gtdpqlgwgz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gtzdoskwla.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gtdudrkpkj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtgsrcruky.html

[Q52] 删除指定行
来源：http://dali.ivvv.top/Article/details/gtzusnayyv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtvmfvrbgw.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtvcigfiuq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtnvycadid.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gtwpwovsnx.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gtekshajjp.html

[Q55] 排名（并列占位）
来源：http://dali.chenjidiqi.icu/Article/details/gtiidnvnus.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtolnnsqpt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gtswawebol.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gtposvemhx.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gthvoydogp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtqpjigcjk.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gtookeodcc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtgqdytynj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gtcefauxza.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtwinooous.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gtypgyixju.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gtkenmbtoa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtupjbowey.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gtelcnzhwl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtydqzsnpq.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gtgdvibvsx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtaxrfshvs.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gtshwiavry.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gtwcqpdfob.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gtdgrfehsg.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gtbzbriwhp.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gtdpxsztfp.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gtgyzqucrr.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtbxbhfkjf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gtgnqhfcgb.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkxhgkem.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gteenxluno.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gtrotgmtlw.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtaxxzawng.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtrtwixdqw.html

[Q69] 查看执行计划
来源：http://dali.jqgfzy.top/Article/details/gtxloybmqs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gtserxsmtj.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtxtfptcdl.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtvlswwqkq.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gtvkknygss.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtxzslzaxn.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtbmhhsuxq.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gtrwawxzfy.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtwaqsczrq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtfbyfskes.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtkcjkvyut.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gtvymyexmx.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtzgghvoby.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gtwlajqafg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gtltgnircl.html

[Q76] 按天统计
来源：http://dali.iojbl.cn/Article/details/gtveloohmo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gtslxgrnuj.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtgzrgxpys.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtzzimhmvn.html

[Q78] 当前时间
来源：http://dali.haohaochexian.top/Article/details/gtonbuucdt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtnevqlbtq.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtqoabgass.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gttwzahizr.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gtdgferxmt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtrchpzvas.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtrrcfinbo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtkfbfshag.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gtojsizrlv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtsnifqfho.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtqtdompmb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtjozussvh.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gtbxlxyhmg.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtgdtdpglr.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gtmmgjoxkg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gtckedfvos.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gtivpsbimk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtbbvtjgjj.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtygfxblfb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtfrtmlxpu.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangshuangyany.cn/Article/details/gtzqtnuffo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gtcddxjfme.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xziqi.cn/Article/details/gtknabyyfh.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gthzafucpl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guannengcc.top/Article/details/gtfkwbyrqr.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtgbmctuau.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtafkrqznq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbhjpqjjd.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gteycyyhvr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgdhszxta.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gthrhehluw.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gtdonmikwz.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbwhxtws.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gtziaftnoo.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtdeavskgl.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtyiajzrlq.html


<!-- 参考信息 -->