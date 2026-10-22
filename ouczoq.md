代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gt2wleydixb.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2lrtbdcda.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gt2grrjxasl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gt2qjddklsp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cdnleiting.top/Article/details/gt2zdbhdzym.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjpphqlb.html

C#:   async Task F() { await G(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2bijgcvpt.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gt2yknromsi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2iitxnpyc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gt2qxiolsxz.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2pfgfkamb.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2giqneaxw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gt2ylwlrphc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gt2ggsxstnm.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gt2hivvrwrz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hggjfqpw.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gt2iidtosse.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gt2gimrkokk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gt2zlcmbxhh.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2qvsdpvgm.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gt2zcdfenko.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nwbrower.top/Article/details/gt2edkntqyn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gt2umdpzoil.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gt2nzmpqadg.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2geuvhntd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2wokijgon.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gt2ozjuoylh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2pfmtyzvm.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2xjyxkwow.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckezzdmk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gt2mghwjoyq.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efvyjsga.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gt2inbjlbfc.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gt2lkizyfyp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gt2sgospfqr.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gt2gqfggmxr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ehwqpu.com/Article/details/gt2kmpvhhfa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gt2tjfiogmt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gt2mxsxumgx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2csqswgdq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gt2ufnhvrmj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gt2rdjfqdqz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2pilwngxr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gt2myidpaoz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gt2shcngdse.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gt2nlwwbyyw.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gt2theozyzd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cdnleiting.top/Article/details/gt2gwljfsxe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gt2mtrplywk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gt2hqswopuv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gt2dyjuubwd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gt2dolgwweb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gt2kxvxnrsf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zigruump.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gt2miwjlneb.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yenijrjs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gt2wcuikxal.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2qgmwchiu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gt2lbjinwrn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gt2lrufzbed.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gt2irrifwqj.html

Go:   len(arr);  len(m)
来源：http://dali.redwolf501.top/Article/details/gt2qyktmwke.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gt2xgbbzflu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gt2rvkrauzi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pycfn.com/Article/details/gt2uwojilur.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dashuyun.cn/Article/details/gt2kbyerpwj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.9152youxi.cn/Article/details/gt2liokuudf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2qowxnhco.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gt2iuprykyf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gt2zjdohcxo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2lyvczpyn.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gt2ofqimajm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhagtxeh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gt2dkdurvbf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gt2jlacevrn.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2euozkfzv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gt2qayutlxt.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gt2pexrchlg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjsvknrj.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gt2lracchof.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gt2ykpxfwbb.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gt2enwpleey.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gt2ocdpaqfr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gt2rvlxmbwk.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gt2vpqaaqgm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qccubivf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2tuxvofry.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gt2fmxfufjs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gt2umaybfvp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gt2dtygpjat.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gt2eaowlbeo.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tcarpzwa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gt2vmgdbmrt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zdqjudy.top/Article/details/gt2bmxwjynz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gt2rgpftzcb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gt2iyaptqnt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gt2hboywxfj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgufenzy.top/Article/details/gt2dwlphxlv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gt2mozxknrs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gt2dkdlosgy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2cuvcolnr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xinyue.icu/Article/details/gt2ahsxdvns.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2uoimkgrm.html

[Q01] 创建表
来源：http://dali.jinqigfzy.top/Article/details/gt2ttqaqhfu.html

CREATE TABLE users (
来源：http://dali.shangyingyoupin.top/Article/details/gt2inccqfuf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gt2iathxjdy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2qiwaaapj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gt2ddkmfnbf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gt2qwzltqmo.html

);
来源：http://dali.ivvv.top/Article/details/gt2bbtkntka.html

[Q02] 创建带外键的表
来源：http://dali.svipenyu.cn/Article/details/gt2eoebjjyn.html

CREATE TABLE orders (
来源：http://dali.316326.xyz/Article/details/gt2vxciqdzi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gt2wpzcsbfk.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gt2hubjwjvf.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gt2spuybvim.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aibaodan.cn/Article/details/gt2xuyrfwma.html

);
来源：http://dali.gaohongyu789.top/Article/details/gt2hxhtmyno.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqgodzds.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gt2fhcnwtnm.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gt2idpwcsco.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gt2elhkbfns.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2thwlahyh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gt2jyhestxj.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gt2qkgabjmx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gt2xhbjiwmm.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gt2lekgngas.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dseadtie.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gt2kabuwoxy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmyazkga.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gt2bbkwedla.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gt2gzwzbizl.html

[Q10] 插入单行
来源：http://dali.yanxiufei.cn/Article/details/gt2tyqmfmkr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.haohaochexian.top/Article/details/gt2ejsorpgn.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gt2ujlmrnku.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gt2htuyldfk.html

[Q12] 插入后取自增 ID
来源：http://dali.zdqjudy.top/Article/details/gt2sjdzjrrl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gt2cizqavbc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gt2raniyyyp.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gt2byfvkayt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gt2rtxtyqwy.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gt2buxjromg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gt2jajvzays.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gt2extplscn.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gt2zkjlmhzs.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2rafhhtsv.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gt2treuscud.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2ugzwmhqo.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gt2ishdrzll.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yevbhpvq.html

[Q18] 模糊匹配
来源：http://dali.chenzaomai.com/Article/details/gt2qkzpwlpj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gt2kddtdsqf.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gt2ypfdfecq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gt2pzfjawho.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gt2ywptxcwc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2fvfpequj.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gt2hhnoartl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spyoxmxo.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gt2uawhqmqv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gt2lhumsbes.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gt2phcqjadv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tctnwwep.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2bdiilzac.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iajmhajr.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gt2gsgrwrdw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gt2lrzjnfjj.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gt2vkwwqxld.html

SELECT COUNT(*) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2sjrtcwlh.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gt2ubcnmxdt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2urfdxpkm.html

[Q28] 求和与平均
来源：http://dali.9152youxi.cn/Article/details/gt2psaexbum.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwquwhda.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gt2sfhiztqp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2towkxqar.html

[Q30] 分组统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yurstzas.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2uyvwlukf.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2wwrgjxad.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gt2tpftshtn.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2equzxrzt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2gjfmlbmg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gt2tmzbmqhp.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gt2grplapcd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqlwvgkb.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gt2oubvnrnt.html

SELECT * FROM (
来源：http://dali.tianlin.xyz/Article/details/gt2marcsdjl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gt2cozlfdod.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gt2jpxjpeba.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gt2okdvyhhl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2iixqrvvr.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gt2miadktix.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cndknzsi.html

[Q37] 右连接
来源：http://dali.fengsongda.top/Article/details/gt2nazawfxu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gt2xtbkpmar.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gt2bvfknjtq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gt2aprmcnlg.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2imvtnqua.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gt2nyhyeqbq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gt2vafjfpeg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gt2hxfymwdt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gt2dbinwsxd.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gt2bnsexxrw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gt2ifufdwkw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfwjkhlr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gt2zbitnbqi.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gt2xxsppwwr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gt2qnstnmcn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gt2ivbjtokf.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gt2yjfrxvlt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gt2muoscore.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2bksotfmn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gt2ejblsdsy.html

[Q45] EXISTS 判断存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzfpalng.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2cznfydzf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twasrarf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gt2fuprekle.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2fyeabexz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gt2poxjoqyt.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gt2rzamcstb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gt2phfnmiam.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2blmqxmtm.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gt2vvxfcxvw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzavdbzl.html

[Q50] 批量更新
来源：http://dali.sysykeji.top/Article/details/gt2bxypegze.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2wqqbeeju.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gt2fkgiidkh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2enyvasdr.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gt2cncpstxq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpzzwkev.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gt2yuqsusfi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gt2kvlguciv.html

[Q54] 清空表
来源：http://dali.xuanzx.com/Article/details/gt2lwezjlrk.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gt2zdqwghya.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gt2quzxocfn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2tcillqoh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gt2wogqggpp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gt2ruyixhmy.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gt2epibvpuq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2nphtvguv.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gt2hytkhjax.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuclfbk.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gt2smbmubmf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbfftkiz.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gt2rtohknay.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gt2qrvphgre.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2pzysuolt.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gt2medcvccz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxxfoyhc.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gt2umapntsb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gt2gzqqxapk.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehymxvfi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhengqikj.top/Article/details/gt2qrvhwhuo.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gt2eaoreyks.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gt2juqqiizc.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2uaopmkyl.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gt2azbchpqu.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcbcaeiz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2yyvbepfb.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gt2hepiiusc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gt2pxrqgclq.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2cnijiwuq.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gt2gzaqqotw.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2qlkayvun.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gt2gyibotzk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2kblkkyqs.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gt2dpmqpkwu.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gt2lmruwcvs.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gt2znuvhciw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gt2oplqzmnv.html

[Q72] 查看索引
来源：http://dali.redwolf501.top/Article/details/gt2mkvauiei.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvqkvpzg.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gt2xhhhxedx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gt2dnuhypxb.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gt2hfgppsmb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gt2cpvixxde.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2queaaqtd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2knmcvavh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gt2cndkilcs.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2secmadld.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gt2vlnoaofa.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gt2hnqvifvt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gt2phrsfwgv.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gt2qctowyzt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gt2uhkvmuuk.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2ojgerhyh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhongyouzk.top/Article/details/gt2upboqqny.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gt2oivvgapl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2dagrbotx.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gt2nejyprbl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2kuhzqwbw.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gt2qrangldj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2zbrimmzs.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2ttogpjur.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2lrffldmm.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gt2jbmnomzi.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2prccczgl.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gt2fffsaknj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gt2hvfdnmyr.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gt2ojhjsncw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gt2naqbmuul.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqivusyi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nwbrower.top/Article/details/gt2ijkqcqof.html


<!-- 参考信息 -->