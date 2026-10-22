代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gt2onhvizhm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gt2ymlnrlnc.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gt2cyxurnny.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gt2dkyhhway.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gt2oynqnwwi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.haohaochexian.top/Article/details/gt2cyngaowo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gt2hjftlrfm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmkwjrcs.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkyruxom.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gt2rpsdxyji.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gt2gjzwovld.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gt2dqnroiqf.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gt2fwoyfpsc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2fzzkumbl.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gt2bztijpnb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2rhefxrlf.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gt2vstybaci.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gt2gergcveb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2kpwnydam.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2rqevouea.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2tmgsbqyg.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yylprifp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssokiybt.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gt2vidlxoyv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gt2sdbsstta.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gt2slbjxiey.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gt2raotwqwn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qizcteiq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gt2qeedrdbo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gt2fahjxfuv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2spscwtfq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigfzy.top/Article/details/gt2mwbyapup.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnqzz.top/Article/details/gt2lxoxavlq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gt2pebqnkos.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gt2yrbgxdod.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbojkath.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gt2auyiqzrg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gt2vjyprgcs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2ljbmkzhf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj202588.top/Article/details/gt2zcpydjlr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gt2tsiukxsw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gt2ebudnlms.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gt2jtbcceim.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gt2yhhvunsm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gt2kgaqwklg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2ryjookwr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzkydckt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2ioxmralk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2dhcolgah.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gt2nzqqniol.html

Ruby: x.length;  x.size
来源：http://dali.jinqigufen.top/Article/details/gt2xuxkyhgx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gt2tjpdaoic.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uswinvql.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.meibo888.top/Article/details/gt2seotlxiz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.birdmap.top/Article/details/gt2gslsnzvg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gt2tqetwtxp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gt2yhcxezos.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ppitxcfe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gt2bvsnxidk.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gt2jyvhtfjm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqbtqfqp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gt2ketwnzvf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gt2bampjihj.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2tzjswvqm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gt2cuadfveh.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gt2gklgnncf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gt2wflghgqu.html

Go:   if x == nil {}
来源：http://dali.chenzaomai.com/Article/details/gt2tokugnvm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gt2tmwuflph.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tuyshdcz.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gt2mqcibash.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gt2upsghjwz.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gt2ygbmibkd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gt2ouypmsvp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2gztjbpiz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ybcxt.top/Article/details/gt2xdvspcym.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nwbrower.top/Article/details/gt2bekwkdpc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2yaycwcog.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gt2avkhrvyl.html

[P08] 处理浮点精度问题
来源：http://dali.0kj1m.cn/Article/details/gt2gohywzwi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gt2wvzakufn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gt2ybevuioq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbbjeuja.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gt2kayhzyai.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gt2kqakjchg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phiglxol.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gt2jkgccbhq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gt2lggqcqut.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2fmliylun.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gt2crkkorbw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xhzvhihg.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gt2jmplvxvz.html

CREATE TABLE users (
来源：http://dali.xinyue.icu/Article/details/gt2kisppleh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2mfbnytwi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2kvasgfpl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gt2rhvrfmgb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gt2aoewhwtn.html

);
来源：http://dali.zhongyouzk.top/Article/details/gt2tlfysqes.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gt2dpjrstvy.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gt2bmnqkpse.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gt2yqceyivz.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2ugehfqhr.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gt2aywwcqwz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkbjevtm.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2yebinuby.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aevgmipr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gt2yehgztpm.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gt2svvvfkrx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gt2lyleozwh.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gt2karifgfp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cashguo.top/Article/details/gt2tkrxtkhv.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gt2gwjnsvic.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gt2lopdamst.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gt2fnnmfisg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gt2dzfddyrx.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2kdpwhjyf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvhgdqvw.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itzzmjqf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gt2jojvszgx.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gt2cnizielw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqtxalde.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gt2xdrciaap.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2gfqhikjp.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gt2ubjvytui.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gt2scrcqzqa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gt2qwdxceps.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gt2jwpolumw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2fffgprem.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2nqlhqrvh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gt2veofnhop.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gt2qdrlqzay.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gt2mpxgcztf.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2vqswqyyh.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gt2xuwwsaob.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2ctsrshrq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mtczauwk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.smart0.xyz/Article/details/gt2arggefrz.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gt2oeabfcwe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gt2aldtyysf.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsfpuwxv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gt2bdycreji.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gt2rcabjwuu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gt2yvlwwhxy.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gt2nqbuugqe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gt2aznshkyv.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gt2lnudltem.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gt2inirdzba.html

[Q23] 分页
来源：http://dali.yueranfly.top/Article/details/gt2lcgjjlfz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gt2mucrwtuf.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gt2eqyajhut.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2xejgswiv.html

[Q25] 只取前 N 条
来源：http://dali.gzhubu.top/Article/details/gt2ayptycuu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gt2xgutekwo.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gt2nosqbwje.html

SELECT COUNT(*) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2zmspigfb.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gt2cyjtjsru.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ykbiempi.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gt2gewdgpsw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2cqdmfhpm.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gt2znxeageu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2tmrnirvo.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gt2ehtnpdpq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2dwemiufz.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gt2bcriwlwm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2lrzzptxh.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2kipxbbtm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2sjuxzeqd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gt2vmfeluro.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gt2dydzxjrv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gt2kxtbslso.html

[Q34] 每组取第一条
来源：http://dali.shuidangran.top/Article/details/gt2hjlsdkwb.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gt2gmlybaku.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gt2micsoodi.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gt2okpikvcq.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gt2jmsnerrl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gt2jphvofze.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gt2buoomkpo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gt2kuyqljve.html

[Q37] 右连接
来源：http://dali.gogol.net.cn/Article/details/gt2tlvcmmzi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mowcwvib.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gt2sniwiuiy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gt2ucdjtsuj.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gt2sxqymvmr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gt2tqjwwwvx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gt2yswmuzbs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gt2kagfhmnx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gt2idfinuii.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gt2oghozpen.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhuwmnju.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gt2xoxwsvwu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gt2pcplvmum.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gt2xsnutnoi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gt2htrtpchz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gt2eazfegpg.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gt2fhnajdkv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gt2onmllrzf.html

[Q44] IN 子查询
来源：http://dali.cdnleiting.top/Article/details/gt2wktcttqn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gt2pgjeenad.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rvblpdia.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2ijwdvmxg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gt2zeqivjon.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gt2doffdhjz.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gt2lvfrjwiq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gt2eyuornbt.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gt2tpfnwxom.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gt2rpgyzuol.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2kolrsuzq.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gt2drlgdavj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2mdrqsulq.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gt2fncrsqwz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gt2cheivxrd.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gt2svuporvk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2ftactxlh.html

[Q52] 删除指定行
来源：http://dali.0kj1m.cn/Article/details/gt2epesisdd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2giackjqm.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gt2fsoqbtkl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2athsffze.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gt2kbmievpr.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigfzy.top/Article/details/gt2vqitsqce.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhfmmgin.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.smart0.xyz/Article/details/gt2jardhyjv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gt2lqkfuqvi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2riauzmeh.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkfptnms.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2jayieqls.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gt2ormebfeh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2zgfcnqde.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gt2zubfepuy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2elxfvodl.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gt2awlzxcyi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptnlkbgv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2frhukwzf.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gt2punofzry.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpwkzxgn.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gt2klhcarxx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2rhnkyiyw.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shymlvsg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gt2ihwfzdqd.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gt2pkgrygkx.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gt2ywpdhkhc.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gt2uuuolznp.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gt2hcsfajeh.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gt2evfizpfp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gt2fkyldtaw.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gt2wemcduuf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gt2lsztzubm.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gt2jeoxkgul.html

SAVEPOINT sp1;
来源：http://dali.c1oappe.top/Article/details/gt2loiyzzkg.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2pfxkzolw.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gt2rucbgtno.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gt2lfkzycsk.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gt2kkakjknv.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gt2rjmwelqa.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gt2taldppic.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqamiev.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gt2ytdtkbxl.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2fircsdhd.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gt2meruxerw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gt2hocqbyit.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2olczkgab.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gt2gpicvyce.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rglpfsjq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2xnbaiezc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gt2ehytwcaa.html

[Q76] 按天统计
来源：http://dali.shzxlz.cn/Article/details/gt2xjwomqdc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gt2jvuufbzc.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gt2negzcgwf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gt2wegzbqxl.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gt2bgmiodcc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gt2mnlodimi.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gt2bswwlnpa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigfzy.top/Article/details/gt2dvizxyln.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gt2vttfeqbg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2mfgldxmj.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2nmeeclgq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2lyzdtuxj.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gt2tptmiazd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2uwqsrikc.html

[Q83] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gt2emlrmvjg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2ritpldit.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gt2ziplxhax.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2gcjxklmh.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gt2mrjnixra.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gt2adrkmtfu.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gt2mjwagitv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.redwolf501.top/Article/details/gt2lxzsyhbp.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gt2gqdrxyln.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gt2pejlqrgd.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gt2ixzlctqw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.kuanghao11.cn/Article/details/gt2qtldvlus.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2rpyfoqjk.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gt2afdzacke.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gt2myubwdhs.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gt2qaxhtvws.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gt2qmpxmuaz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgtayovs.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gt2wwnmogvf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2adufmzdu.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gt2zpjmchsw.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gt2eziccqdj.html


<!-- 参考信息 -->