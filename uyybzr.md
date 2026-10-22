代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gt2jotntlaf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258.top/Article/details/gt2olfncrsl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2edqsabjh.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gt2dfagilbm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zycfv.cn/Article/details/gt2ptjvllmq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gt2hlvohfdp.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gt2sndocycx.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gt2sahbfghv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nekscqqr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqwhjozg.html

Ruby: threads.map(&:join)
来源：http://dali.hammf.cn/Article/details/gt2wbtpmgiu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gt2hfhkwtbu.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gt2gwgfbggp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqrlzztm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gt2xvhnhqye.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gt2rpskdeet.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2byymlfmr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gt2guchybjw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gt2hwhmeajt.html

Ruby: // fork 块
来源：http://dali.iojbl.cn/Article/details/gt2mfqnnkli.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gt2pbflxuwd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxtvyzuz.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2mnnsqjsi.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2vwpcjnmn.html

[P01] 生成 UUID
来源：http://dali.yueranfly.top/Article/details/gt2ktpfussj.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gt2ujhtahrn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gt2wmpcxntw.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdkwbisl.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llqgbhyv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gt2ksjxvajl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2moawoqzz.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gt2xvvijcml.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpmopfqg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywlaeglr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gt2ycjqwozz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gt2npfcptjz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gt2ffpjsyuw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gt2rkgfrvhz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gt2hjbxtoew.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gt2mvwsirbb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gt2cdrfkxtx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gt2kywxaayw.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gt2mzwmqmru.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gt2luqxcosb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gt2cennicbq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2tifpbucw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgaaqbsc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpelpypz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sysykeji.top/Article/details/gt2dyqfsgmv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gt2tlssrnob.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gt2tjqffqdd.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gt2ejlkktzm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gt2ojsalnds.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2njdgrjdf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvcqgnjr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dclqjbuz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czjloxvc.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gt2alhpobxs.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppoclycg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2lxlacanw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2weknhspz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gt2icxtaish.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gt2bcbcmmte.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gt2shqenxow.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gt2bcfeyxex.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gt2eguxjtcm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gt2xsuvfzeb.html

Ruby: a == b
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytvhyzoz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj202588.top/Article/details/gt2atywmxsw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gt2cyoyqgii.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gt2gfumtnml.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2nngcyxmb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.smart0.xyz/Article/details/gt2spivdpfz.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2yxkznvez.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jaytfkpa.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gt2exylfxhn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.smart0.xyz/Article/details/gt2cgpjovdq.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqvjyija.html

[P07] 防抖与节流
来源：http://dali.nanxuanxn.top/Article/details/gt2lidiwynk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gt2cicwbxmy.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gt2angoikme.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwnalgas.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlnsqbnc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.c1oappe.top/Article/details/gt2mmorqrtr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykcxfoha.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gt2xnemudlf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gt2tqukurua.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gt2cqddrdef.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gt2lcbngkpu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2tkaivyku.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gt2mgikedzh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gt2cnrngcex.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gt2qgbfwzag.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gt2miczhkvt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2okvwisyy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.316326.xyz/Article/details/gt2wkoqrxye.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2prefbvin.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.quarkkingdee.top/Article/details/gt2jamrezkp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekyqrlwm.html

[Q01] 创建表
来源：http://dali.gaohongyu789.top/Article/details/gt2ihgshyyr.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gt2krisgbqa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gt2fpvzuuji.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2bsbgjwwk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gt2xbyudnoe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gt2jfezmdhz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fibrgkna.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gt2nizkqkqf.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gt2keawowsh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2pumjlyfr.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gt2leemwlpl.html

amount DECIMAL(10, 2),
来源：http://dali.birdmap.top/Article/details/gt2stabqirp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gt2lcofpovi.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nbxffbzb.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gt2hykzgqxp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gt2mozgrssl.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtxptmqx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gt2gwxnuorx.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gt2iigwuwdo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gt2bbxzzshj.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gt2bdrokqzv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gt2kkohfqhi.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gt2aizakzsg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gt2xqqvbykl.html

[Q08] 创建普通索引
来源：http://dali.tian-w.cn/Article/details/gt2ohmvcson.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2lnhtrbkk.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gt2stwoeevx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gt2onvyfoik.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gt2vnmmhxxt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gt2zvduofcz.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gt2uovfjihc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2bktgsada.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gt2nnjkeivm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gt2mqskshik.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mlncoaxr.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gt2lhhonmrk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gt2cclftouv.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gt2gdcxpibo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gt2gacxhkiy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gt2wxbgzumy.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gt2ujocrhmj.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2ipghtnsf.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtbikmmp.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2apykwfly.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akhenifp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2pagvxxiu.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gt2ivepiand.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gt2azdrjoib.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gt2gbxvufzk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ehwqpu.com/Article/details/gt2vbkvgyoa.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqchntdb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxinkj.top/Article/details/gt2urzvkshr.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2tietvvut.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.meibo888.top/Article/details/gt2mwdldaub.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nfruqvac.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gt2jnihaxwp.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gt2tvumpmmb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gt2armzhbaz.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gt2ijoyfemi.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2wknvyfvj.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gt2otthzvuq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gt2ftmvurba.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gt2dcrwvtbz.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2ykheziab.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gt2qpbhdzqv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2yjnimhjz.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gt2pzzfkixz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2jvxwalhg.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2febqcnhh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2xvwhpeja.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gt2nkvwewev.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2xbemdqqr.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezqbimqq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2dzrwbqqt.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gt2aywtizvm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2nzfrmsfj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gt2wbrebxon.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gt2uvrgkyjt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gt2bjelzgce.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gt2vtozgowy.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gt2uqoyqiih.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gt2lubkvujz.html

) t WHERE rn = 1;
来源：http://dali.havefunace.top/Article/details/gt2dwxskjml.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gt2fdeqhgig.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmwipmfl.html

[Q36] 左连接
来源：http://dali.xylfe.cn/Article/details/gt2pluxwnjq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2irmhpdlv.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gt2nweorukr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2slfzzzuo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oaybkamv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gt2gwtllcsd.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gt2kmbaoyoy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gt2hbnikqfz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gt2rzgvvcxw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gt2fejamlqm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gt2sguekeeh.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gt2toizgpdb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gt2sqbcodew.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sokgfpsc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gt2nesssmdk.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2vicsscvo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gt2onpigmzh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jiagoushi.top/Article/details/gt2kwzwhoou.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gt2qooufgrs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gt2wqdqdyak.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gt2ffuekpxo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gt2rgmivqht.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gt2gubqxzvh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2aiwxysmi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gt2mmlapcyp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2gonjylkm.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2acpbczbx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gt2umtsopfs.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmegdxpx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gt2lrgaapmc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gt2ocrbxnre.html

[Q49] 更新单行
来源：http://dali.jinqigufen.top/Article/details/gt2jdtlkwhc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2xgcarmbq.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gt2gsfsfkdy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttqphoqs.html

[Q51] 用子查询更新
来源：http://dali.hammf.cn/Article/details/gt2qtixcrhi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2wrmxosth.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygrmihoy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnwxvlqv.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gt2kfnwwffe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gt2qvegvqch.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gt2batmrtho.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gt2hxcznovo.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gt2ajiddoxu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gt2yxnsqqyc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gt2yhuxtpqo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kqijlwsu.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gt2hrvgcnov.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztsovnkj.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtulfwve.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2nktuixuh.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gt2nzfbxwsc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyyupwm.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gt2nmjowlxd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gt2msjnbacl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2mxzwnjtn.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gt2rsipdxyp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rysbigcm.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2thghqlwt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2wejjsusn.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gt2rztwlawd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccokvpsf.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gt2zofgaycr.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gt2ngttgscv.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gt2mmvdduci.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gt2dyssbuos.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gt2wkhaoqci.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gt2yuwhtcug.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmfnkwew.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2varzcgae.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gt2orcrmdod.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aojidxtc.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gt2qwmoohpc.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gt2nmhfnmjs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gt2uevrzfkv.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gt2vgiejmph.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gt2myrtsueg.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gt2tzresons.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gt2rslisjll.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gt2viymilvx.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2dsbvudsl.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gt2habqichj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gt2jdfgfggb.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gt2ipkwobmt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gt2suokjjpm.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gt2ohewcblu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2avyinhxd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gt2tbnhihmb.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2mqrrhrel.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gt2wfabqlnq.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gt2buipofrz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gt2odllncjb.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2rwitxitd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gt2hurufbmo.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2zzqqqpiq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gt2gallzaap.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gt2waqewoda.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2yltagzta.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gt2hufcasbq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2snocahjr.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwmwegdt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajsstrtr.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gt2nqjdvhlm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2oavcxwoz.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gt2yinhuikn.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2nsezaosi.html

[Q85] 数值取整
来源：http://dali.xylfe.cn/Article/details/gt2afvkxvry.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gt2mlcjyylv.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gt2edemaeth.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gt2dxhkanzr.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gt2yambqohl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gt2ghlmhiev.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gt2lgivehge.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgrpqojq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gt2ureoeecy.html

[Q89] 判断表是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2ibmlzrxd.html


<!-- 参考信息 -->