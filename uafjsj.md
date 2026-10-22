代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vunbewbm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gt2zyzcfkzk.html

Ruby: threads.map(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vttgckfm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gt2iyjyegwa.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gt2nssaluha.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2jdebreti.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzgnqmuh.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2gzidulcj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2qsvxatju.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.c1oappe.top/Article/details/gt2xcbhrtzp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gt2hpyylsve.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gt2evakpglz.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gt2ctypkykt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxmxagwl.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gt2sbnhpdmh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2kbjvddtt.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gt2duukbhac.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsdismxm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2rsjrlkec.html

JS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2mzkzayse.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjijhmah.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gt2ykkvkyfj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gt2rtpibvxc.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gt2mcwjqvxz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvdtxblh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gt2gugoycqa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gt2ejpsenjg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2kkgbhkol.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gt2cbkmxeas.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gt2ugfskcrz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2iwykbwsu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbnvisiv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gt2zrffofvr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gt2bopifwtd.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gt2ktlktzea.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gt2ubidjjhy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gt2qmfgfpdi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gt2vclhedqn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gt2oclkalis.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gt2fakxbxpa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdxurbyn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gt2dvdjfmoy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gt2jzauwrra.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gt2slclnvym.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gt2pntbfwke.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2ftlnlhvy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gt2lgnyjphp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2kosuycnp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2wkjrkdka.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gt2jsijrcnc.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gt2bdbrwktf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2manoldzj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gt2dtqxpmgi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gt2eivsbuwg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gt2rfzfvprt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gt2dksljcdr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gt2sfutgvsu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gt2feivikqo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2alvxmksn.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gt2xbqpjwjz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gt2puowchat.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gt2jhwuevbk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gt2fazzzfax.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gt2bwfkwqga.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gt2eapezszz.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gt2lnakbdtq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2bxebhgde.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gt2pfhhkyhv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gt2glrvmmzz.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gt2ayujmtwa.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gt2uvekysjc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gt2lzqwncre.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gt2kqpjrniy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gt2ftmcsucn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2sumxkznq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knjwusvj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqqtgcl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgufenzy.top/Article/details/gt2ckzuoefk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gt2efnmraew.html

[P08] 处理浮点精度问题
来源：http://dali.ehwqpu.com/Article/details/gt2spmiqaov.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gt2efdgblap.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pycfn.com/Article/details/gt2wirsykgf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gt2paiexoyi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2qqjvbtgc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuanzhike.top/Article/details/gt2zevxehux.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gt2tovfbgkz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwboeoyj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gt2ksyzqrxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bulpznds.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gt2mzxisubi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2qzbcpwma.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gt2acrbrxqk.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gt2efbeooel.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gt2ayunltji.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gt2qmcqxffq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gt2chhxrgcv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.0kj1m.cn/Article/details/gt2tkxptelw.html

);
来源：http://dali.cashguo.top/Article/details/gt2uafhexqc.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzabovog.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gt2ifdbezpm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gt2qtmhgujx.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gt2kizbtkfr.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gt2qqgaabal.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gt2enshvavi.html

);
来源：http://dali.zhengqikj.top/Article/details/gt2wnrykxnn.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gt2jkvskyfw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.snrcjt.cn/Article/details/gt2qpizpvwe.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gt2vzduqpfi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gt2elsvvvsx.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gt2zmtzjioy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gt2srmtfwbk.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gt2ttngrdcr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gt2viqrejtt.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gt2gykxamzu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gt2nncgdufb.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gt2gazmlimg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gt2yypwpxbj.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gt2fsfxhnvz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gt2xpgyopwt.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzasilpu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2spbaidih.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gt2qzllpypf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdadgmuy.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gt2zqacyxqi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gt2dgxjfkso.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zdqjudy.top/Article/details/gt2dbxrcldr.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gt2pvuutdtl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2jkahzmdd.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj202588.top/Article/details/gt2pitohiew.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gt2uwauhvbh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gt2lkpezkkc.html

[Q15] 查询全部
来源：http://dali.cqqwz.cn/Article/details/gt2qokdddqg.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2xbatwxbx.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gt2nvijnhuq.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2lgwvgruj.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gt2besiexrl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.smart0.xyz/Article/details/gt2vufltulz.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2qijzzlco.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gt2scpaauik.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gt2tnfohxph.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gt2fmvdxicb.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gt2znzbqhtu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2qmyzbvdk.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gt2epckolhy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gt2qfbhvntd.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gt2wvvnsyxg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqjxailu.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdbldmdy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gzhubu.top/Article/details/gt2ruvzoapv.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qigukdvw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpcakntl.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gt2liaiqgez.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gt2akeqsbrq.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gt2krwwucpt.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2skbsjeqx.html

[Q27] 条件计数
来源：http://dali.sxryk.cn/Article/details/gt2podilgzk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2wssqirxk.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2uascqgpm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2mfjfzggm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zsamfglb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbefvevp.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gt2dwkettln.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2cwabpcqb.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gt2esxygbje.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gt2cnbriopd.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2mzegaozw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2ntmtnvxt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gt2umojviio.html

[Q33] 多列分组
来源：http://dali.haohaochexian.top/Article/details/gt2emiltxmq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cucudq.cn/Article/details/gt2thunwiuc.html

[Q34] 每组取第一条
来源：http://dali.cashguo.top/Article/details/gt2gvgjfspj.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gt2oflxnowb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gt2mtlodkrb.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gt2svcvaehv.html

[Q35] 内连接
来源：http://dali.jyoumei.cn/Article/details/gt2ntroosde.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2wqbxmmru.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gt2upimcvrm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gt2ysvgsizp.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gt2cftcoxho.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2nrfxxmga.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gt2gfakdpmr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2ytokhxmr.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gt2bcfbfkrd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyugtiw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjgncjxn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gt2qhyubbis.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yuxfuchg.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gt2rgvgzafu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xinyue.icu/Article/details/gt2aasansmc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gt2llkzprdy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2ndcjnjwr.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqnibutn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gt2ybluyqhd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gt2mqtlwheq.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gt2gjorejyv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.316326.xyz/Article/details/gt2inbopgvs.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gt2dwuyecbu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gt2pmdrblgg.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gt2rukkcukj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gt2ddlceidj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gt2vdtyotvp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2abvgbhyg.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2qfbbrqor.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gt2safdythw.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gt2ozyalgkb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gt2jhdasgci.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2nfvomrui.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gt2xvicqmjp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2igrbtiqf.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuoapmln.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gt2rxiiengz.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gt2yfoieuti.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2wrhkvhaz.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkiiizov.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2aalpauar.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gt2oxmxpkza.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gt2fqqdtfnc.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gt2zgusjdym.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gt2tjouftku.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gt2rtvyvwqu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gt2zhwtkmvx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gt2xizhdgna.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2cadcdsef.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gt2lauroqze.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2uvjoyxga.html

[Q58] 累计求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqlxbhgb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2nztsttoi.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqqwmpsf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2xvpmikqc.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gt2bmwtqjus.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gt2gzehneqm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2yqeftlng.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gt2tlpylocd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knyttmeg.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gt2hyjpwjnt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2eupxqaks.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gt2stfckpbi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.birdmap.top/Article/details/gt2myrijkdk.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gt2hxxfqqnn.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gt2emcxshkc.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnyublcv.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gt2cpdhoihd.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuonwhyo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gt2qylukeyj.html

[Q67] 设置隔离级别
来源：http://dali.hfpthk.cn/Article/details/gt2ritudbfm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gt2fxgffcjr.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gt2hmflffuv.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gt2vsbhsdks.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gt2jzsgbkol.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gt2oxkppgce.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gt2fofrdzsl.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gt2ldfqudjj.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhgunkvz.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gt2levbzali.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aicmeybj.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gt2uhxumyph.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2dinrqvra.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gt2empyimty.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2jzigywaw.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gt2ptgwfrdq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gt2ocmubybg.html

[Q75] 日期格式化
来源：http://dali.pycfn.com/Article/details/gt2hiryzfwo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2jfeyeehp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gt2ywflhwwi.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzzscqar.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gt2aupudyqs.html

[Q77] 时间加减
来源：http://dali.wangdashe.top/Article/details/gt2stzucbut.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gt2bchqfmly.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gt2itnibkuq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gt2givzuhqh.html

[Q79] 字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gt2nhfkplqf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gt2viezndds.html

[Q80] 字符串截取
来源：http://dali.cucudq.cn/Article/details/gt2klahwpiq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2wgqklygr.html

[Q81] 字符串替换
来源：http://dali.yj202588.top/Article/details/gt2pnyjarnd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2guxppjdq.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gt2zcypkrno.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2vwkaisxx.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gt2egzenakg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2qechjfho.html

[Q84] 去除首尾空格
来源：http://dali.hnqzz.top/Article/details/gt2ammyymqh.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2panwzvri.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gt2lozwtuvz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gt2ontpkkkw.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gt2iitljwnr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gt2igpkgsxj.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gt2tdrarwpe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gt2xfteracn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gt2xngcjwtm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gt2snhtnfgo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2quazkloe.html

[Q89] 判断表是否存在
来源：http://dali.jqgufenzy.top/Article/details/gt2kzsrgxkd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjdgbdmd.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gt2wfnzivrd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.havefunace.top/Article/details/gt2drbjgihx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2idjscygv.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gt2woqwvfzu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2pvimwtiy.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gt2xpyqduui.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gt2viudvacc.html


<!-- 参考信息 -->