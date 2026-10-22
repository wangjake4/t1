代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gt2onjrfxwk.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2etvrilip.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gt2kuhxykyq.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gt2kgbzftic.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gt2cixafetw.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwzobrvj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gt2cyqmjxme.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gt2knvvsalg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gt2bgqhpsja.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gt2fujwekif.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gt2lxadsffc.html

[O05] 并发执行并等待全部完成
来源：http://dali.sysykeji.top/Article/details/gt2qicrkjsm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2aybfnrni.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fotbyqak.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2wluebbmt.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wabpoxxc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gt2xkwoecwf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gt2rzcnygzm.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdacgmpi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gt2sjyxbzua.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gt2wwnwpbtj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gyzhqaks.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yonumen.top/Article/details/gt2pwqbywpf.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gt2wgqkxzgi.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2axpguaya.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gaohongyu789.top/Article/details/gt2nwyltcem.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhoulong.xyz/Article/details/gt2tqnupegn.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oinappnj.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gt2hmjiseos.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2zjhppoqx.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gt2jzkuxajb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2bhanonvf.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gt2qlzvybjs.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gt2gldnfpho.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asdaumid.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gt2pgvyrflo.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gt2tuphhbkp.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gt2lzbzphvu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qauniwmo.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gt2zwlrepjf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gt2oovcbdkt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxvngirz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gt2dyuwmcms.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gt2hpdstlxa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2glnhaoxy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mntmkftc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2myupjqef.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjocedjd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfodwnxe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gt2vlvyygzv.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gt2wogzhvmv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gt2namrngfx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gt2bnskxcdv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gt2pbehdnkz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edvwhbtb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gt2ntaaqhsf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gotoacloud.top/Article/details/gt2nazopqbc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdcefyug.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gt2iechxryd.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qysuryda.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gt2szdvgddx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2uqihyhno.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gt2dwsqtjjm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnvsotfr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2meytjxiw.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gt2zxcgcmiv.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gt2myfwqwzi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gt2vkwyfayj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gt2swximloy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gt2njwrgfcd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2heylyalj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jyoumei.cn/Article/details/gt2ieoocuyx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2iezycjyu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gt2byfvcmsv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gt2wgypxxok.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gt2xygvtqju.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gt2gfjgjsks.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gt2hurinfoy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gt2kwzsjlpe.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2uiumvnzu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ehwqpu.com/Article/details/gt2pfhrbzrx.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gt2haymfcct.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aekotfqd.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gt2tbeyjuyt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gt2zpyskrjq.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rytbkzut.html

[P07] 防抖与节流
来源：http://dali.ivvv.top/Article/details/gt2sojyscwk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gt2eedjxrwd.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gt2wybnwani.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2doffirpc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gt2jrlpxfsh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.c1oappe.top/Article/details/gt2mosequak.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gt2kcvznaoc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sufxvd.cn/Article/details/gt2bqztbgnh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlueebiz.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gt2olepdtta.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gt2oxqksmoh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2lbcfmdcx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gt2crrpdhlt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvjdwmtz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuxming.cn/Article/details/gt2vbijsjlv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gt2gymxvsoc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gt2agogobwt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gt2fmeqalio.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2qdjlxkck.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cashguo.top/Article/details/gt2jxniimma.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2urskwbxl.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gt2lipdhpmj.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gt2rmkqigxp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gt2nhhjqknu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2ljsfnfvk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jyoumei.cn/Article/details/gt2idstnuez.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gt2wszpmzzs.html

);
来源：http://dali.cashguo.top/Article/details/gt2ebzptwkc.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gt2ffdfvyeq.html

CREATE TABLE orders (
来源：http://dali.yanxiufei.cn/Article/details/gt2unhquexy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gt2iiuckfym.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gt2mangcwtg.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gt2uzujyerm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gt2hsbmvldo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aufjrwqy.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gt2hmwkdaxn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gt2ostybdzw.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gt2wtqgmpex.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gt2qdsupyjl.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yupunbwl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gt2raykyeyu.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gt2yvrpvaug.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gt2hssvnddm.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gt2gyyaoaql.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hngesmab.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gt2hlqcqtqn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2egkixryx.html

[Q09] 创建唯一索引
来源：http://dali.0kj1m.cn/Article/details/gt2rpngrmsc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2cxnlkukf.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afrbpapk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gt2zdhhdiba.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gt2kwfzfcqq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2tdwulxvv.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gt2kwczygat.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbkvbkul.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ehwqpu.com/Article/details/gt2xcwykhrm.html

[Q13] 忽略重复插入
来源：http://dali.daria6918.cn/Article/details/gt2ttrwnmpy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2jldzjxdz.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gt2tdouzple.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gt2inlbanum.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gt2bbdrurfj.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gt2yqtbfvyg.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2ljvpagpm.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gt2rqbsvpre.html

SELECT id, name FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2zucrgmir.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gt2nhbvwcpl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gt2ctdydqwn.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gt2tlhvxqih.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gt2qfrqcxii.html

[Q19] 范围查询
来源：http://dali.bjfxy.top/Article/details/gt2roqempsk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gt2qejcaoal.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gt2owamzimx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2czpjfkft.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gt2bbcdtibu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gt2vbwegliy.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gt2qedkttbo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gt2rkfjlsky.html

[Q23] 分页
来源：http://dali.dianchejie.cn/Article/details/gt2jahvgvze.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gt2vfffpzts.html

[Q24] 去重
来源：http://dali.cheryme.top/Article/details/gt2ckfwrvmz.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2uvofzefr.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gt2zatqcven.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gt2htidkenl.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gt2wiynnjnc.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2bevwsgle.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eitshsta.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2wvqgejdd.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gt2toczvlwg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2ezxbhfaa.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gt2brjsikme.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2oljugpri.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gt2njdtscse.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2qwlbnojo.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gt2ihainlre.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2wzpioezb.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2kyjkthyp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2qohnnayg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gt2hfqjbxfs.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gt2ydjktimx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gt2uodenvxu.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gt2mzciguzh.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gt2xeejkuwm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gt2trofnyzc.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gt2nshbldjv.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gt2twrubqqx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gt2gpnbwrld.html

[Q36] 左连接
来源：http://dali.nanxuanxn.top/Article/details/gt2wqxbxffw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2eowgxvpc.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gt2pdexcazv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gt2jaenquam.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.mhx1999.top/Article/details/gt2brdgiuri.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ppjwa.cn/Article/details/gt2nivbudac.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccaqejqc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gt2xdnxysyg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gt2gqqjvkth.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gt2dhtnlcii.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gt2qzznqpcu.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gt2lazjvhgj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjoggdl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gt2rlsdcnmr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrrkhynk.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gt2ropqymco.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gt2tzagfcqr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gt2kbyjlxqq.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gt2qlvzuuxb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gt2dnbyqipc.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gt2qmlvhycd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wicxrnds.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyrrwnfd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gt2hziyfmkg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2zxxgbjdf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gt2wlhbupai.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gt2poxlklyv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gt2dbgtisfn.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gt2eexnawdz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gt2rsfubrhm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gt2gzytcgfm.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gt2pyncwwbo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2kkpvsfrp.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gt2rgiyvpws.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gt2czkkdsxw.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gt2znvtmqea.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2knexbvqu.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gt2sstufoxc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gt2uxmwwbnr.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gt2uzjkyndy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gt2nisyjpfw.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gt2spyevsif.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gt2tjieluqa.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eakfkwno.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gt2kqullnzi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gt2pqlqomtg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrldvait.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gt2exlziyjt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jowfqotw.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gt2tmxlbzor.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2phwuxkey.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gt2hbuyhngp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2pqwjzgpx.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gt2dhxyrwjy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gt2kmaxmirp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2izmrkavk.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gt2hlemvhjk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2qsctvvdj.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gt2wnxxasjk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gt2lhnxaizz.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gt2wtydjvls.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gt2tomjqiwh.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gt2ydburttm.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gt2cmeudxkv.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gt2iyssbykb.html

ROLLBACK;
来源：http://dali.9152youxi.cn/Article/details/gt2bqrqsqch.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gt2yrftaumk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gt2vlfslktr.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gt2vlnfpprt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gt2giopfhli.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gt2lhyaoclq.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ystpfyol.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwwwhth.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gt2qqfghotn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.kuanghao11.cn/Article/details/gt2twrflito.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gt2xlcrpgke.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gt2twswitwf.html

[Q71] 查看建表语句
来源：http://dali.smart0.xyz/Article/details/gt2tbwwytrb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gt2zekgvpyp.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gt2nljjicwm.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2lzxvxcqy.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gt2pywjexdt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2bepcjwmv.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gt2enmcholk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gt2oczzyhtt.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2otnayakz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2bcqetrxt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gt2sleahcbk.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gt2aqoaexwd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.smart0.xyz/Article/details/gt2skrzvhnc.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gt2onkcvjsq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gt2gbuhiawq.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slcztdvq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gt2lgomptbj.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gt2duhwaznh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2denlzgov.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gt2dzhpvmlo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2bfkzafts.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gt2tpexfvdd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2qyjqhgxq.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huahyteq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2vzvywndj.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2hoxfczqf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2tecefami.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gt2zblzmqsg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2sxahohnx.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmydslsd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gt2nkvfnble.html


<!-- 参考信息 -->