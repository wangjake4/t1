代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2zlircewj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gt2rdnlkqzm.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2pqufzvju.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2apmvhbwh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gt2wgutamdi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gt2gmtqgmqu.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gt2ewmcnzto.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gt2kuhgacei.html

[O06] 使用进程池
来源：http://dali.yangfankeji.com/Article/details/gt2kkegmbnv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gt2xljtuins.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sweek.top/Article/details/gt2dudjkser.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2gjhtyyqr.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gt2bqxfsewd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gt2lnzaqchr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gt2dcwzzsql.html

Ruby: // fork 块
来源：http://dali.pycfn.com/Article/details/gt2trjqxlia.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gt2mstfzktf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xuuuorzf.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gt2geusutsx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2cntatfwy.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gt2tbqiiykz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onmiqexc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yangfankeji.com/Article/details/gt2utspbnhl.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2dawwihap.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2nisficsv.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangdashe.top/Article/details/gt2zmexqnum.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gt2txpmdmdl.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gt2rayttqep.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gt2xocdfbmb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuanzx.com/Article/details/gt2jpavpkqz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gt2kbddhsfq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gt2ejnlofsm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2zvilzerw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gt2ohwizoek.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gt2ooglvzzw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gt2omhddkvq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gt2wjqrltyo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swklehds.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gt2axvgszqi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gt2lwldqgzu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gt2vkmfmbkp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gt2fhflqdcp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2vikbfnzx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2vhvfsxez.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gt2xqdsjlla.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gt2ldhpylyr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenjidiqi.icu/Article/details/gt2uklvealz.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gt2iyrxbibt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gt2zangcuts.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2irrecpma.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2wbepapwu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gt2osbgizbh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cdnleiting.top/Article/details/gt2vwtcuifb.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gt2hujpvwwr.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gt2wvyrvcrs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gt2gpyxkedy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gt2iknliyge.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwauitbt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shzxlz.cn/Article/details/gt2bkdkmbbl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gt2tiujgbku.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2moqbihpv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daria6918.cn/Article/details/gt2ftvapvnk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2nkhzsxcp.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gt2hrbdzohp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gt2xqhaniyi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gt2qbhvhuhc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gt2qfkowhns.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gt2jozmrbuh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gt2iznhmqth.html

TS:   if (x == null) {}
来源：http://dali.cashguo.top/Article/details/gt2rarhsppv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gt2rguzddhj.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gt2quzfazup.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftnthftv.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gt2hjxzvfvc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nebsnxbl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hammf.cn/Article/details/gt2ovplrsis.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gt2kfdunjjy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2bcbtzygj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2hpuwgrky.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gt2uolykjzo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gt2nzbrtkgz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywmuicjl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gzhubu.top/Article/details/gt2ounanwmj.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gt2bhfxjrzs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gt2kacerwxd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzvvkekj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gt2krcvwgjx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gt2wyjrihcd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghlnmnaj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gt2nmtimvbo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gt2poacbrip.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gt2tsvoyylb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2setgtvpz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gt2bqeqlhzh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2xomgnsks.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gt2beelbnnk.html

CREATE TABLE users (
来源：http://dali.iojbl.cn/Article/details/gt2kqvriqqe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2dvwinpqv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2bbnzwjya.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gt2jwqccpmo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guannengcc.top/Article/details/gt2lnbcomqw.html

);
来源：http://dali.tianlin.xyz/Article/details/gt2xqjunorb.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gt2iklplutq.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gt2uwxkxikb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gt2dznoloif.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gt2awebrdjl.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gt2gquvvlrb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gt2wdxhbwdh.html

);
来源：http://dali.mhx1999.top/Article/details/gt2ysajyucw.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gt2rbcpamgw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gt2xmpbiblh.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gt2upznqwul.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gt2kprfqcyk.html

[Q05] 重命名列
来源：http://dali.redwolf501.top/Article/details/gt2bohufklt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzwpwtrs.html

[Q06] 删除列
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhouzdzp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gt2tlcqarli.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gt2dotnanba.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gt2uadowmzr.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gt2xedaxfbt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gt2twbgdnhf.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2epatgmxm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2rnlounti.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gt2vnhxadpr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gt2jrmjqzwu.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gt2kwoyaocp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2suqffugd.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gt2nrkrukau.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gt2mmzhyurk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gt2hlqhbyfz.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gt2mxqbbgrc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gt2ztwjvkhb.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gt2uihjeasm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gt2hekpevjy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gt2tteuksyd.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gt2fxleehij.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2ijxxdmvh.html

[Q16] 查询指定列
来源：http://dali.havefunace.top/Article/details/gt2ctanbibr.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2ffixoxba.html

[Q17] 条件查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czjnyumh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gt2jrpraxrk.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gt2mvokemvl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gt2zwrionxt.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpvrjyzy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gt2kcmmmrqp.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2oackkiel.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2nmyqlgfd.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oefmcnci.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gt2nonubdux.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gt2fpquyhac.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gt2ingbnqxa.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gt2zjtuwtbu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gt2bvdxtqze.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2gueetafr.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2jpvasane.html

[Q25] 只取前 N 条
来源：http://dali.xziqi.cn/Article/details/gt2ueyzgphw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gt2fzzzfrik.html

[Q26] 计数
来源：http://dali.yuanzhike.top/Article/details/gt2epwgtoew.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2wxdsrtol.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gt2ieblehnc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2ybhulwgr.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gt2sjnqroth.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2rjkcpepm.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gt2guhhsgbl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2xyaalelw.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gt2stivzojc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2syoifjjr.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcakxjmj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gt2yzeimfry.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2jdvkpbem.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2yodyzmhe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gt2qqfivyfp.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gt2feypmpit.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gt2ozsfbamn.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gt2dppptotp.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gt2lfugrbxh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gt2gpejrydc.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gt2sigpvtyq.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gt2lskfxxcj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gt2zjvtryow.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gt2zqhrehva.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gt2ahdkvbyq.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gt2gkrqrotv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gt2hzrrlrpx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whhfczkr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gt2mvqzvrrn.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gt2hnwsynez.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gt2yuhlqych.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifgmdrii.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gt2prdsigww.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gt2uqqebwkn.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gt2gcjekzia.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gt2bltqumkh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gt2hwnvtttg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gt2rtxqfnmf.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gt2zxmanrsr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gt2iiywvyhl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yvedp.cn/Article/details/gt2qfmpbdym.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gt2ljrlmcqr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gt2bmwitkte.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gt2lbjmlred.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gt2ysdorbvr.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khqtlvdt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gt2sgjhcimf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gt2viamjrek.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2bsplzjda.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gt2fuygsaxe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mfphvtpw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2bauhvmlm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ybcxt.top/Article/details/gt2bnujrudy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.snrcjt.cn/Article/details/gt2jasmzdfw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nkojwtyu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gt2ymjrxfpu.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bimqwfbu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzpiulxa.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gt2zgylkoqo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yueranfly.top/Article/details/gt2olfnkaof.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gt2ylheowaa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2bgzfuffy.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gt2midovjey.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdasxzef.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gt2vlzsibcu.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gt2kixhwdni.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gt2igwpjijn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2bztfxbwe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cheryme.top/Article/details/gt2mcgjchxq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2afzjbucu.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gt2luhuvcmp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2gvkzckja.html

[Q58] 累计求和
来源：http://dali.gogol.net.cn/Article/details/gt2wmcfbhoo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2dhbncgsh.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gt2eudpksra.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2bqeqircj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2aoumsoch.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gt2aucyvkyn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2udfdmrqx.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gt2bljhqlux.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2dajwlbsz.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gt2vvjehqpq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2swuquguq.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gt2rcuzsofc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gt2mnpanhch.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gt2xcbdoayu.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gt2hdzkcoct.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gt2gffwnllu.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gt2ipwdzjaz.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gt2idojtjum.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsgypfzy.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gt2ndqfeydp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gt2pnbjuupg.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxpfdjka.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gt2qkoqunta.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gt2bnqxmssx.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gt2qldxzrev.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2ajdbqfsc.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2acxhctsv.html

ANALYZE TABLE users;
来源：http://dali.mhx1999.top/Article/details/gt2lxadiazb.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gt2gapmazbl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gt2ewprnxuj.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gt2andoifzt.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2lwdeuxyd.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gt2ybqooicv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gt2uzdwlndl.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gt2hgdavwht.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gt2ijgpzggf.html

[Q75] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gt2xexatpkv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2leodfglw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gt2vrolrpok.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gt2djaxkqfn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncdbtimz.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2sjnzbpmp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gt2uhufrltg.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2mnucaemp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gt2mqazhrql.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gt2juowaued.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gt2puyrbyze.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gt2cufvvjwz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2ccrycmtj.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2yccpvfny.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gt2qhxiqbzw.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gt2mcjromed.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fivzmssu.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2twwwuccx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2bhksebsl.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gt2iwzpzpbu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2gorrraqz.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gt2wihwvnol.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gt2iyjemnll.html

[Q86] 读取 JSON 字段
来源：http://dali.ppjwa.cn/Article/details/gt2isgttccs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gt2jlfpjzrb.html

[Q87] JSON 字段做条件
来源：http://dali.jiagoushi.top/Article/details/gt2ktqjceho.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gt2ohimefji.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpliwatv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gt2omprjdxt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2kolmlydo.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2svxwfqrg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2rqddgqzj.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gt2dwmvrxaa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdobbpkb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2sinqbbth.html


<!-- 参考信息 -->