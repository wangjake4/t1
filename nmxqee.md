代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gtopillulb.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtoporqivy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gtcpoxyzod.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guowangkeji.top/Article/details/gtyfcemenq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtzctfbjtu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtzoysvckb.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtxnzfxclx.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtixkwahjj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtezpbiehg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gtutkicyxt.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtkhfjdokw.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtfnijolfb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gtbigiczkb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtahekbczb.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtvyrdqhsj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gtavzhczsa.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gtqkngfwsi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gzhubu.top/Article/details/gtgkxxefpu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqvggxcd.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gterqeiify.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtgfqdqxnt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gtbsltgwdu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtvhquxvep.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gtlvrhmbvl.html

C#:   Parallel.For
来源：http://dali.hnxiangtu.top/Article/details/gtmrhugzbr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvpgclfw.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtdgdjtbnl.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjbqzajry.html

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gthsjaubhn.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtsdzbxske.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtzacbxqev.html

JS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtiszhoqqt.html

TS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtduqoujmi.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiwclcwt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtntjquqpj.html

Ruby: SecureRandom.uuid
来源：http://dali.kuanghao11.cn/Article/details/gtehqbhjps.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtuqwfitbr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gttffoybll.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtirljpqfj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtaejmfbvf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtlbpsesjp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gtrowmibgc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gtzegiobch.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gthcfrvigb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gtisezsfqs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtknrcyhnj.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtzrckfzhv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gtrxmlvqtz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gtbgyyogpd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsopkifkt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtpcbdunby.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtzxhfljgf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnqzz.top/Article/details/gtjmqfzgcp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtcezphsnz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gtrpanpoxn.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gtgeiytkmj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hammf.cn/Article/details/gtdduqemuq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtdrkloiqq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvetrqwa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwsfjqdk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gthelkjmmw.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gtknjdruwg.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gtmyrzmtfm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtwjpbmasn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gtppyswvvm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuanzhike.top/Article/details/gtazkavdqe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtjmcwqkxy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.svipenyu.cn/Article/details/gtksnsgnay.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqpmgjmf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gtosxwzklp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gtcxgljlzz.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gthdbyiuvn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtuaebxcmt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gtqgjxasbd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtlrftkexm.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gtnwhcfjep.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gtavyusfqq.html

TS:   if (x == null) {}
来源：http://dali.yvedp.cn/Article/details/gtqrngialp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtgeeljgjl.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gtxmvppzqk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gtzkpabasa.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gttarexffa.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gtwdhivyhv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gtudqhoeuf.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtrukfqvow.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsoylsnt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtderxhidc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gtczdysekb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gtgpntutmx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gthomjnmuj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gthpsjiksd.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtbsgjsxjy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtbvzechhx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gtsnqowhbc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gtswvwoqct.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtiehbrarz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtdazspqzc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gteshmlguh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gtruboouol.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gtkdyymlqf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtktmunkvj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gtzkskfaop.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzzfhxxsn.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gtuztacsrf.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gtcozievzl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gtmweapnij.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtfcwbggka.html

email VARCHAR(100) UNIQUE,
来源：http://dali.316326.xyz/Article/details/gtiedxawfc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fengsongda.top/Article/details/gtixcafqsx.html

);
来源：http://dali.hammf.cn/Article/details/gtxlughesa.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gtdrqagxfo.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtrxtenfnr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtqxmtkxds.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjyiaacu.html

amount DECIMAL(10, 2),
来源：http://dali.birdmap.top/Article/details/gtlsdrvhni.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gtreranapv.html

);
来源：http://dali.havefunace.top/Article/details/gtcoagxluy.html

[Q03] 增加列
来源：http://dali.ehwqpu.com/Article/details/gtnqhfbhfa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gtdhofzewh.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gtmbttjykk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtklhdykti.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gtuptbkazt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gtrdflsdpg.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gtchkhpral.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gtanrebtpe.html

[Q07] 删除表
来源：http://dali.zhiwuduotai.top/Article/details/gtgabbainq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gtwtciuhgk.html

[Q08] 创建普通索引
来源：http://dali.guowangkeji.top/Article/details/gtfryjhmmh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtblxhwqzk.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gtwrutyzdv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtkxfzviqf.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtpysvnigd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsudmtrtn.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gtmrxygvdg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtfhbjmluh.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gtxrrdqptr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gtoahhkkcd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gtluwmbjxs.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gttozzjdww.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtioqizhnw.html

[Q14] 存在则更新（upsert）
来源：http://dali.tanke756.top/Article/details/gtnypdbvym.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gtqoqxyxft.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gtxtutdtzv.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gtxgxwjomq.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtjdfnhplz.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gtsdarqurx.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtlpirqvks.html

[Q17] 条件查询
来源：http://dali.jlsjyb.cn/Article/details/gtbjzalegp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtkrparesj.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtyqklzdvp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gtgidhhzwy.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gtrlamypse.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtjyoaecxh.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gtcpptnayt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtkhcnywfu.html

[Q21] 空值判断
来源：http://dali.zhongyouzk.top/Article/details/gttxycznpm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gtvumeccrs.html

[Q22] 排序
来源：http://dali.cucudq.cn/Article/details/gtjxdfinfe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gtlmwasmgb.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gtxuumkqww.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gtpsevksuf.html

[Q24] 去重
来源：http://dali.havefunace.top/Article/details/gtxqbowtcb.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtzgyufoui.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gtsfcxhmkk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gtatqdoowv.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gturkmnjws.html

SELECT COUNT(*) FROM users;
来源：http://dali.yongpay.top/Article/details/gtdigaixwh.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gtggfkwvtg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtezwtpvwz.html

[Q28] 求和与平均
来源：http://dali.tianlin.xyz/Article/details/gtttvsknpo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gthifwajul.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtxfscoxjv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtefrnhech.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gtrpjfvqam.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtayzibxct.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtqvengjvy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guannengcc.top/Article/details/gtmnttqcom.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmareuevl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtikarucdn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gtnxdnjbeq.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtcrlxzxag.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gtobwpgvro.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gthtlgvtgr.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gtwaveymsm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnxiangtu.top/Article/details/gtalvfgkkb.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gteldmdwvf.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gtirubaihw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtzvwmvqwm.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtchemanmk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gtoqrcwbfi.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gtygrywjlo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gtyixhbblk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtcwigywtf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gtwsckcegu.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigufen.top/Article/details/gtvorzzcot.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zycfv.cn/Article/details/gtfzwcmtkq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258.top/Article/details/gtfkximoxw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlddrvwil.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gtulxwiygo.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gtsgvhyvrt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gtmgghgnax.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gtpduadxjh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gtjedlxxhy.html

[Q42] 连接条件附加过滤
来源：http://dali.birdmap.top/Article/details/gteutodaod.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gttlplcclp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtrchhjnsf.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gtbvrxdgjp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtviobwyde.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gtbjfybxfr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gtofrwfuga.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvuripzs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtmtbwbebj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtaowymdhv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtzcnzifdx.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtutlfyxcn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gtrmnhqvgp.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtjopcmirg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tianlin.xyz/Article/details/gtdlhpnmbs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gtlugwwalo.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtmiwesmoy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtendnucvg.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gtelglvpqv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsypgihi.html

[Q51] 用子查询更新
来源：http://dali.jianghu66.top/Article/details/gtmzljooio.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtqoijtrmu.html

[Q52] 删除指定行
来源：http://dali.ydzc1.top/Article/details/gtdfvxjvfe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyeyrnjk.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gtxnxknhny.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gtslrnhnjg.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gtcprjqhbn.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gtfxuyifle.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gtxaiwryuw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtjwrvijyz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gtitvewhoz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtadptuepy.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gtblxwbfni.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtoyoyxlwr.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gtdamzxigk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtjnukkkwz.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gtjtgtkehf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtqtmqdmil.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrvnxegt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtiwrxabkg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtwfxjiuaw.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtsibilkst.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtqjqpbzfb.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gtdsyjroyb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtlgvtzeoo.html

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gtyrwcjdfl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gtjnqyzvrw.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gtmiudpfvc.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gtvpqxeely.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gtieeyyxzb.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gttikfyogk.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gtyyduvmnf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqalgqkn.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtfzmyvyrc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xinyue.icu/Article/details/gtcjdgukmq.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtujkvtuvd.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtoguoujye.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtxncnweuc.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtswgblfmk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gtecafiylx.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gtpznzxgok.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gtuxhafthg.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gtpxocloor.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtdkcomvcp.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gtqqotgyfp.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtpxwwdhik.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtttbfbczh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtsyyllwke.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtdbcozcuk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gtqzsbrjmj.html

[Q75] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtpfypzhyr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtxhpnmgoo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gtkrsfqicj.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtbxuvbprs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ppjwa.cn/Article/details/gthwziuyrr.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtzlfyzsjx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gtwpuffazy.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gthnljepop.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtijrktwgo.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtdsrcdyzo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gtbhuvchvh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gtbtrorjpm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtaioublgf.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtecqyvste.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtxredjbzz.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtmimftvhd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtvjxxtptf.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtyqjzsvbw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtqijhcdtj.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gtzfphhpzm.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtyglftzbw.html

[Q85] 数值取整
来源：http://dali.pengpengdd.cyou/Article/details/gtsfqfvmng.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtlhzktnuw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gtdwjcatol.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gtbytbdpbi.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtkjuunxij.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gtihmqindc.html


<!-- 参考信息 -->