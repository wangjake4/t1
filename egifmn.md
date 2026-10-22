代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gt2okavkqjk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sysykeji.top/Article/details/gt2ogweqteq.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwfhmuft.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gt2ffkzidfq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuxming.cn/Article/details/gt2fykwkwoj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gt2ewqaqjvi.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbpcocha.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdlnzept.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gt2sxgnnbes.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gt2mtmkfizj.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2itaxqyxn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gt2sbjwdkuz.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejshumaw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gt2vgodmmop.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gt2hojncunz.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gt2blwmrwfx.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gt2hwzomyal.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guannengcc.top/Article/details/gt2lmjbaori.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gt2kimmkcfq.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gt2hssgehyu.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gt2kptkvzxc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2inwobgwx.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gt2emhxvpdc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2tgzdqbvh.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gt2sifpddkm.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gt2kegazzis.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gt2cbttkcdd.html

JS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gt2ewhcuzkx.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2bxamfghl.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrmpbrct.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gt2qmufitfe.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2brfdfimj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gt2dofskfby.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gt2mwuzsxyj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gt2hgiwydgg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gt2carjhtzu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tianlin.xyz/Article/details/gt2afrqhrgv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gt2wzrwufbq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2rchhmcoh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdpyqukw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gt2atvslakm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gt2qkfbdujy.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2scztevac.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gt2qliwlhxj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gt2estynqzh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2oboviikt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2jhkbxluo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gt2sifjercp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gt2gxlcmbgt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gt2nizlgneg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gt2xwtgnrpu.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkxjezxp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gt2qdspbwjw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2eioahxva.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gt2bogtzyfa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gt2lpkpozeg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gt2lwmqgvsf.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjpoxlwc.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gt2qyytzolh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2godxsjfv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnqzz.top/Article/details/gt2kvawoctq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gt2zwnucfvv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gt2mqtnqoyu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gt2ojskbnfu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gt2tqizpvhz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gt2ryuscfdk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2fyhdubwz.html

Ruby: a == b
来源：http://dali.mhx1999.top/Article/details/gt2juyrumvw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gt2ofnoftqp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gt2fucsfnpt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gt2qhkvvosd.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gt2idwwnost.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gt2xknahpdw.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2fbdaexou.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zwmyrhoi.html

Go:   if x == nil {}
来源：http://dali.svipenyu.cn/Article/details/gt2yzrgthxu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gt2jnsowaxt.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ueaqztra.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gt2jvzaqwhd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gt2gmnnuluu.html

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gt2cyczmome.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2jauxapao.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2lbhtbead.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ofeiavao.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gt2ngkqkpxy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbkncltu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gt2gblpeuaj.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gt2xmiuavum.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gt2njyuiddj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gt2lwmkbhqh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gt2akjfnhee.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gt2tbcmnnho.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gt2dficktxe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmmawgu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxuanxn.top/Article/details/gt2rtwcevpv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gt2givahsit.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2myqkxqeu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gt2pvosvqju.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2vtbdmopa.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gt2gpwifvkh.html

CREATE TABLE users (
来源：http://dali.jinqigufen.top/Article/details/gt2xvhuifqb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2nyvvpxqt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gt2coiafagt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kytchzfc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxuanxn.top/Article/details/gt2sxvbscqm.html

);
来源：http://dali.yonumen.top/Article/details/gt2ldhydrzn.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gt2lctutrli.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gt2parpabqf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gt2sblxvtgg.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2nwmukzgu.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gt2oigvrxjr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gt2jmfqqdlf.html

);
来源：http://dali.zhongyouzk.top/Article/details/gt2lneextkk.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gt2vybdlsiy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gt2piketnjw.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gt2yvstwtgx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dafasgev.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gt2rqvhlckh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzaotnp.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gt2hcipinyj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gt2jbqohqny.html

[Q07] 删除表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hojuvquz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2ymzzpruc.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gt2quakpkmc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2lumqfqas.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gt2eitgwuqg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gt2otkpjsil.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gt2terakzij.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2uehunpej.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gt2qxqgloqr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2suaprpcw.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gt2fzzccyif.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gt2vyigdarf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gt2xfrxaczx.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gt2rdqkyyts.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gt2xdorubtx.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangshuangyany.cn/Article/details/gt2shefapwa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gt2nolcrohs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnqzz.top/Article/details/gt2exwdjerl.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gt2scnwhwxt.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2vzgmhkay.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gt2qhnoljck.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2ghgjyisk.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gt2bjfncajs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2gongcjqa.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2dxnernak.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gt2qxsjvxod.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gt2ljvlkijj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gt2iavxfyym.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gt2pqrmjqsm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gt2otdokwro.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gt2mwfxlfqj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gt2qdpijvlc.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stvshuob.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gt2ufytmaac.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gt2qzhumkex.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gt2mdeptgfq.html

[Q24] 去重
来源：http://dali.jinqigfzy.top/Article/details/gt2artvuzva.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2zpnexuvf.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gt2ybnwrths.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gt2darotxbg.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gt2fcgglsur.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2rmoxgrra.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gt2ltmdpyfd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2mjczdfju.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gt2ejrsvtyj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2zgvbntig.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gt2ftxdprfu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzgteqbi.html

[Q30] 分组统计
来源：http://dali.jlsjyb.cn/Article/details/gt2jmvnfzfv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2gsljmluj.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odkyswll.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gt2tbucvfvr.html

[Q32] 分组拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2edcoikuc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2tdfezjdv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gt2pivjiswu.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gt2guguvbvj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gt2tdsuhymd.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gt2mpdvolou.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gt2cfbpbsri.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gt2aajtkddy.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gt2eatujepl.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxgcwtln.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2tmmofslw.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gt2pqgyidte.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gt2nkqeglmc.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gt2hdlzkkgx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gt2iadkxhxp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gt2ivmvmssr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gt2ewklkzxb.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gt2znewdlyq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gt2hdtatftu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxlpjkfa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gt2hzplwtjn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gt2ppmorcpu.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gt2qseuqdgm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gt2atxiptye.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gt2cshbqdki.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigufen.top/Article/details/gt2ztzadqsm.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2liaztova.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guannengcc.top/Article/details/gt2agngsteh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2jvmokgpd.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gt2gpmsuhza.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gt2aaucvahg.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbtskmkl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gt2ccejaiwg.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gt2kdleqrhs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jimagxia.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gt2xrrpetat.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gt2qdogpeuy.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bojjtcfi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gt2bdadxmyr.html

[Q48] CTE 公用表表达式
来源：http://dali.svipenyu.cn/Article/details/gt2nmrxsbmy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gt2lojtzwbk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guannengcc.top/Article/details/gt2epvdjsbt.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gt2qcrielwi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2pcznqarv.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gt2tvpknvvc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gt2ucpxowny.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gt2rxnwdeml.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2gmxuxyfc.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gt2fecjusdr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2swnroovh.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gt2culakolc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cdnleiting.top/Article/details/gt2zmsekpga.html

[Q54] 清空表
来源：http://dali.hfpthk.cn/Article/details/gt2slvgvyhk.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gt2moyjgsvn.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gt2kudwoxgj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gt2bhbtbwjz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gt2aipqibzn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.redwolf501.top/Article/details/gt2dlquswny.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gt2onfisdby.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2cidlqevi.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gt2zpulupjz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2rznbygrb.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gt2nrohkuys.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2hnfcvgfr.html

[Q60] 取上一行 / 下一行
来源：http://dali.316326.xyz/Article/details/gt2pcnvuvbk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gt2gozlwlmj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2hffuvbvf.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gt2vfkxcxis.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2gvpcxhca.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gt2nftznqvh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2srkzqbra.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gt2mwppuugv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gt2ngozpjdp.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gt2aupoauve.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gt2xxhpneku.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gt2lbmdgrqt.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gt2tpanhpjs.html

[Q66] 行锁查询
来源：http://dali.xylfe.cn/Article/details/gt2ibohqajs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdnnpbst.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gt2cnkmdmdo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gt2ugwiyftq.html

[Q68] 保存点
来源：http://dali.hnxiangtu.top/Article/details/gt2znyfgwdu.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gt2fzxokkip.html

ROLLBACK TO sp1;
来源：http://dali.yangfankeji.com/Article/details/gt2kgacxlnn.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gt2cnhrdytt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gt2pthwkjed.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gt2nxzbammr.html

ANALYZE TABLE users;
来源：http://dali.yuanzhike.top/Article/details/gt2wfrujtpi.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwldutnf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gt2jclctyva.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gt2akkmxedh.html

SHOW INDEX FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2cahcahga.html

[Q73] 查看表状态
来源：http://dali.fzhhl.top/Article/details/gt2czzfhpna.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gt2kunsibmn.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctonthwx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gt2uxlyzery.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnngskfm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2jsarafen.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gt2fhenkrrk.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gt2nwnzqiat.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gt2aivqlbjs.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gt2vtmptrvs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gt2bapzliay.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gt2usljvocd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gt2uvdnrhqj.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajyhlrdt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gt2nhvspray.html

[Q80] 字符串截取
来源：http://dali.yonumen.top/Article/details/gt2dczgkoom.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2jypavbkq.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2qdirvciq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2znbulcuw.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yelwnoln.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2vswjkvhj.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhbgdjpn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2hpxxwycc.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gt2vvbnhszz.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhdpguvq.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gt2yxdyjaur.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gt2isrnnzqk.html

[Q86] 读取 JSON 字段
来源：http://dali.ppjwa.cn/Article/details/gt2aonfdvmy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gt2vojyoypf.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gt2mlxdjmzl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gt2fhsgqeta.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gt2ztecexjm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntlbqlwn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2ebvqczey.html

[Q89] 判断表是否存在
来源：http://dali.daria6918.cn/Article/details/gt2kooueziz.html


<!-- 参考信息 -->