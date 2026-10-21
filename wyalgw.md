代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtndchhvbb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtofvutxoh.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gthvqlumvp.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gtiguhmuef.html

Py:   asyncio.gather(*tasks)
来源：http://dali.havefunace.top/Article/details/gtjetetsnq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gtoqgtnopf.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtaldxkijr.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtkuingqvf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.feifeiyinyue.top/Article/details/gtpdysefrf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtfquzhhcc.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtadgsddwb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrtitsjc.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtcuvbvihb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gtpauwgdxf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtatacnipf.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtmhjpsfkl.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gttpqlltxi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtrrixinlz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gtgzmofvjb.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjpydipw.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtuypgmxlg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtplonyjnj.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gtsmcfuvfz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtzpupcajc.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtpzuothks.html

Py:   str(uuid.uuid4())
来源：http://dali.ydzc1.top/Article/details/gtpimwyobe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtlypltwpq.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtluaedyqj.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gthekamivi.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gtbxrnbipl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtucwhfilb.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gtsytcyraj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gtatfpskbl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gtiemmvljj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gttmlekhgl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gtoodkyikz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gtpdijsbpt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gtkjrcyidb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtvrdfzrmw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gtvokwukvg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdswdzgnr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gtwnazrtfb.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtzjhictiz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gtvyccprev.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gtmoracvgw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gtsxbujpnd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtigcomvwl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtivuhfinw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gtqeopfsct.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtvtycfggt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gtvmqemzze.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzymiuen.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtycotadnm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdlbxuzj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtzvsoftao.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtncdgrcqj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtcpvtrezn.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtsuzhaerx.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtnqybkgzw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtbjdaqnqy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gtrkvrghao.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gtzcskkxnd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtozsapxnt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtqowkrspp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtxzaixcgr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjhiwfib.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gtfjhrhftm.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gtnidiurii.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gtdlrkvjqr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenzaomai.com/Article/details/gtnrfbvult.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtnixksksx.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmgtqeck.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gtadpmngxe.html

TS:   if (x == null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqwhrpfol.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtegmughvg.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gtbpcetmce.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gtzjsuvays.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gtlspofmyz.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtwpialcry.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.9152youxi.cn/Article/details/gtzcevjdnj.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtqdgcpspf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtztlqimqu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtcruiygqo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gtoerapyhi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.kuanghao11.cn/Article/details/gtjifbmcsy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturkpuolv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gtamcppjnt.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtrjlymelh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gtffeypuzr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtcutnewho.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gtfejoekgg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtlbhlmsuu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.snrcjt.cn/Article/details/gtauhhalne.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtfycjswep.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtmvrgbgiz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gtdaxpgsib.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbzuzjpvh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtfixtwyyc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjnrvrywk.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gtpgllgiec.html

CREATE TABLE users (
来源：http://dali.cdnleiting.top/Article/details/gthbncdxnq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtnbfwgqig.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtplfzncnf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gtthadcyue.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gtkedzkczl.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtplyvoksw.html

[Q02] 创建带外键的表
来源：http://dali.yvedp.cn/Article/details/gtqjdxnphj.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtfbcjwyif.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtviczpbpx.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtwaybmpfu.html

amount DECIMAL(10, 2),
来源：http://dali.guowangkeji.top/Article/details/gtqfqlvgwd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtxmtsgrwr.html

);
来源：http://dali.chenzaomai.com/Article/details/gtjgncvntt.html

[Q03] 增加列
来源：http://dali.svipenyu.cn/Article/details/gtijuoiveu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtspzxsvhh.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gttjmcuenx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtufsohjzt.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gtklcgqnwd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gtfjwovrys.html

[Q06] 删除列
来源：http://dali.cqqwz.cn/Article/details/gttupbfsyq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gtjyncpxxk.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gtxfuinjbj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnirgnnpp.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtoesalpjt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtcjdrkkqo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gtfjnfumxv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtswglihma.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gtxkwnvxox.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtxgqkmzrf.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gtgngowyuq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtrmjopeuy.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtjspyfrlt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gtorsnttxi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gtehxbsmnc.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gthdwtxeny.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtwlhaketr.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtwfojloao.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gtmzifulki.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gtbedmfyqj.html

[Q15] 查询全部
来源：http://dali.yuanzhike.top/Article/details/gtqrwsfcnc.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gthsywoyqe.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gtfntvneor.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gttvxayfuv.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gtgxfofxii.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtdmwrtdjl.html

[Q18] 模糊匹配
来源：http://dali.gogol.net.cn/Article/details/gtkkagrkex.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtjzkxztqh.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtcdmrbobz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gtddeloqvo.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtexejtysp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gtmdpnbuwi.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtcwqbotqd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gtennfgyfr.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gtbtklfdfu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtmzwgimmu.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gtchvbtwmn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gtyhxucycx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtwcjvrrdc.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqosjurng.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gttdecqzka.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtnerinmdz.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtchxkmgbk.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtqmypmeol.html

[Q27] 条件计数
来源：http://dali.jqgfzy.top/Article/details/gtdymizzac.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gtahjsqccw.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gthxfdskjm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtsvjiatac.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtnmwnelpi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtclevyiqt.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gthymbzaph.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtbmjmnhai.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtdcethoqr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtjbuqpnlf.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtumlunzun.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtqaaqyoaq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gtvnxkwvvq.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gtnvwpeaxb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gtqcbfieca.html

[Q34] 每组取第一条
来源：http://dali.zhixingplan.top/Article/details/gtsgqzpxkc.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtdgyahelc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gteynrqhtv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtwfevwspq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtyepmdrsm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtzxytywoa.html

[Q36] 左连接
来源：http://dali.jinqigfzy.top/Article/details/gtebkfvlls.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gteaqztnbs.html

[Q37] 右连接
来源：http://dali.gogol.net.cn/Article/details/gtmtmultfl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gtvlmsyhbc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.mhx1999.top/Article/details/gtadgydfin.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtwauqfonx.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtcvzxedtu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gtimzqjfqp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gtyuxrksbx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tianlin.xyz/Article/details/gtsxspizfx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258888.top/Article/details/gtyuynmeut.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gtlgktjbhe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtykpybukf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gtjwjhylzq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtzouphwes.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gtxonyjran.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gtmqaabpyk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtrzqepmgc.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtazrhubkj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gtqaierhgw.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtbytaygiq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gtbkymdyfb.html

[Q45] EXISTS 判断存在
来源：http://dali.c1oappe.top/Article/details/gtvdvyfjnu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtzkhsabdq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gtdseeymvq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtuijsdoky.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gtopqdqeic.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.meibo888.top/Article/details/gtwkaqiblc.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtsuksuzkk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gtlsslbdnu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ehwqpu.com/Article/details/gttxcjtwzu.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtjmeblsod.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtdcnknbtc.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gtxapdsosc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtuuwbegqt.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtwztodfsr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gtcuogtani.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtmncqxmpz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtbwgswnhr.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gtfqjunkpe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gtmdsygyok.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gttvinhney.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtejskfshy.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gtppimvwyo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtjvvmavmc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtpzjfipoa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsrjqxde.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gtbevbwmbo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tian-w.cn/Article/details/gtotughrpy.html

[Q58] 累计求和
来源：http://dali.tianlin.xyz/Article/details/gtxjwneyyu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtmdvfdetk.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtyznuizoq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtsmermrdi.html

[Q60] 取上一行 / 下一行
来源：http://dali.yvedp.cn/Article/details/gtefgphidr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gternftahm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtclowekyv.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gtwozeazxi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtiwvapmov.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtctyzdruk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtxhgoepkv.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtbksinsfo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gtnjmlgywc.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gtplqhtbmo.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtzvryqgmn.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gtpgfvtbqi.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gtdziwapec.html

[Q66] 行锁查询
来源：http://dali.guowangkeji.top/Article/details/gtgpairtrp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gtqgzokesk.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gtpkckvzsd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtmaqjwxdo.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gtemqncfga.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtkvkogwnc.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtnyifjrny.html

[Q69] 查看执行计划
来源：http://dali.jqgfzy.top/Article/details/gtduqtoezr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gthlmgzzbd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtawiotfyl.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtbzgusdtb.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzmwlkly.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtywaanfkn.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtyoyhrfvx.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gtnzcmxxzc.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gttqakwjnw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gtcfzpwvsp.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gtmrcosflf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gtetccfcmc.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtubpjpxhn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gtiyxhfaqf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtbvkfgocq.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtjvyustid.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gtgnlasyzx.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgspszgq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nwbrower.top/Article/details/gtqqvittdd.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gttkckomyt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gthbqntkqy.html

[Q79] 字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtjcyhfsyl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtghkxcskn.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gtcacfslsx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtkzrqehcb.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtcvxwunmo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfecbykba.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtsnnmkwnq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtffcrofzg.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtgibelzdf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtbzguyjrd.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gtsizomxzp.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtgxubigrl.html

[Q85] 数值取整
来源：http://dali.snrcjt.cn/Article/details/gtumqztzgg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gttuprdhua.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gtdlnyeool.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtmnszcrjp.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gtlhwqjqry.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gtyszvgljc.html

[Q88] 行转列（条件聚合）
来源：http://dali.meibo888.top/Article/details/gtwcsqyvwq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigufen.top/Article/details/gtiepnkhkq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtverilcln.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gttfuzsvkx.html


<!-- 参考信息 -->