代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtguybevcy.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdzinsgq.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gtbgolcmdg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gtjajuhpka.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gtyrcdusia.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gttrjbibxb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtzgwpviov.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtfymrlywa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gtedihewgj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtayjvqtfv.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtculobyqj.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gtiyadsyhi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtaanozugx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtbvqnrvyu.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtwczzqqbl.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtgddrnxxv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtaywmvqwe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gtabwzszdt.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gtkbgtjlpw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gtizuryvnq.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtmwchhmrm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gtsbqyssgl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtmmvftzif.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtgutumavm.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtaisougxe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gtcvnanhxm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtfuzogtod.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gtmtjwbnji.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtlfnukqnz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdalhtnel.html

P. 常用工具函数
来源：http://dali.aizwys.cn/Article/details/gtocsuyqcy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtswzgoqqc.html

[P01] 生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gtzbrhmrdi.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gtclgrkshw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gtwmhoytvu.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtagoididz.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzirlgmsj.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gtqczbuzwi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtciaqshan.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gtqsrdedcs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgufenzy.top/Article/details/gtxcnknojo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gtuyhadabb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gtrrhgwwcp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtygwhzuut.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gttptrbszz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gtoiogzllu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtlxmgmuhg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gtuqtakkix.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gtcrvuqcul.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtteefytzz.html

[P03] 生成短随机字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtbayiiflf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtudwdvqvv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtuilhjoxd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtplplzygk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtsuslkgtc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtteszgztb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gtemrbxneh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtwfszfilw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gtglurkrxs.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtmmohdjcm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gtuutrzhrl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtyzoicjwq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtgyueryff.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtyhyfhpip.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gtwfdyjric.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gtohxzyqrj.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gtyxezwxbw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtqruhyxwz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gtbwssjmvl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gtstathsdr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtkvpykvtz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.smart0.xyz/Article/details/gtppskkrxy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtorbidxqo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.feifeiyinyue.top/Article/details/gtslxxllto.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtucufxynp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gtzpybzvjf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtkzyetfhu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshiptlef.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gtxvkeydlj.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtgnblsgnt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gtnoazejtx.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gtavduxbjf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gthpigiwup.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtwpqtjhhj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.haohaochexian.top/Article/details/gtcvgicgbx.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtxayjltaj.html

[P07] 防抖与节流
来源：http://dali.yj202588.top/Article/details/gtvhuxtalh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtjhibqmdp.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gtnyucvfdm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtcxlsceaw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtnigwxgzt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtajpzrocc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tanke756.top/Article/details/gtsobqosot.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.smart0.xyz/Article/details/gtjysfestk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtzydoeszy.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtyjlgmogd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtaorxsvcr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqwkkegx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gtbcwhziyh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtybeoegzg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtzxtfbjdr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hywenlv.cn/Article/details/gtkymbsrsj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sxryk.cn/Article/details/gtufdtdckn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gtjmjreyrb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtodrycmoa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gtrdypzfeq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdwlewzde.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtiipdvmgi.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxcubqab.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtzphqdrdj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtdzavrjrr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtosmnprbg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.svipenyu.cn/Article/details/gtzqoxivjw.html

);
来源：http://dali.tianlin.xyz/Article/details/gtoadekusk.html

[Q02] 创建带外键的表
来源：http://dali.nanxinkj.top/Article/details/gtftsqlmfy.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtbwmvsgbx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gtmesdvusi.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyebsajiw.html

amount DECIMAL(10, 2),
来源：http://dali.0kj1m.cn/Article/details/gtnbcepfwc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtxnhipqmr.html

);
来源：http://dali.quarkkingdee.top/Article/details/gttrvdmler.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gthfrilkhm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aizwys.cn/Article/details/gtzfnecsec.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliaqmgvz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gtciqncsjz.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gtfzjpjwki.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtlfasgntk.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gtpkmhmrvv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkasnuhv.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gtntmiicya.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreehdapf.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gtalilsezv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtkjusamwm.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gtzqvfkjcv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtpuehknzt.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gtglkkuhri.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.meibo888.top/Article/details/gtssakjklb.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gtbfwmfjyf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gttominjbo.html

[Q12] 插入后取自增 ID
来源：http://dali.hnxiangtu.top/Article/details/gtzsnwlhoc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gtjnghrpkh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gtwqpvxwvv.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoimtvwe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtgbmixqwu.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtddkxuomg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gtrbnfwpre.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtweqvhadj.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtmbtgxzcy.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gtcgjeprpv.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtdzlikevt.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gtqfnmztog.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gtfxhtsder.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gtjdrarjpl.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gtwnlfmvkw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gtvsfmbamr.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gtfmeptbth.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtubtezwpr.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtampljekg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gtzkxxyuyb.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gtaeuygcws.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtntofukzp.html

[Q22] 排序
来源：http://dali.fengsongda.top/Article/details/gtttphqusg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gtrogpdvvk.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gtpqfhltbh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gteophiajk.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtyykwwbem.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtxqoxskfp.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfnpdlvv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gtqejezoyh.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gtorecuuhp.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtkhqraakj.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gtestgdxgo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtyqdkront.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gtpqwtkhyf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gthftromlb.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gtnkudqyjk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtsrrkqyjd.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtfyzerxhi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtxfhpmprn.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gtjhxetjdy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gtimqkzqcy.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtdettxlzu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvwmxsho.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gtgtcjlbxl.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtbvjenbnl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gthxjjidqd.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gtrdurvjvy.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtbxfydyfh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gtbbjlmnzu.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtnbenrlny.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtfjnvzwuy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtcbxrwpwc.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtivhybwdk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtxubddmsh.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhcsnhqn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gttbvihjwo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gtlezubndf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gtsqoulwnj.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gtkbhljjly.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtjeygpwud.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yueranfly.top/Article/details/gtmtzlfbgd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gtwwokokvo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gtvrvqqcps.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsapvbplw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yanxiufei.cn/Article/details/gtvrfrlcqe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tian-w.cn/Article/details/gtqejnsjck.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtinakuedj.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtojisunwy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuxqxidu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtligmvcgm.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gtmrpgnjxf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gtjhdwsdfa.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtquqrvutl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtmwmgtwef.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gtykcjuhaa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtfyqtbalz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gtocamsmuq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtsoykmkuy.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gtwukxxnry.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuxming.cn/Article/details/gthivofgzj.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gtcousdrla.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gtiziofoea.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gtnzacysrh.html

[Q49] 更新单行
来源：http://dali.aizwys.cn/Article/details/gtlxoihyux.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtudtvmtrd.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gttwqobhby.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtluglfizn.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtwupauvoq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.smart0.xyz/Article/details/gtibravdym.html

[Q52] 删除指定行
来源：http://dali.ivvv.top/Article/details/gtesdqfbuf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtagcblnso.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gtkqbthyks.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shuidangran.top/Article/details/gtvmcfirdr.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtarmentok.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gtrpwxbvfo.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gtwqyqadmm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gttppxvula.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gtycaoqbjw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gtskxbohnk.html

[Q57] 行号
来源：http://dali.snrcjt.cn/Article/details/gtgiesvcds.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gthrmyimrb.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gtrvgdxtul.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtaafjvysi.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtpoewfjfg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtzzaomeqq.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gtnurlqvnl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gtqevptbnx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gtoxoxwifg.html

[Q61] 移动平均
来源：http://dali.vqdsnc.cn/Article/details/gtjkdkujvu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtbhqglmup.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gtuphalqnf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtjgjgnyjd.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtyvyevrmk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtinopxvvp.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gtdyrcdrfl.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gteffcfzuz.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gtnjssacwi.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gtdcjlwrht.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gtaqzguash.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtlfmogkfl.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtremcifsb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gtbhkxsiev.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gtvohzddxh.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gtoeddclbr.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtchdfpzap.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtyrgqqblt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtgoathezz.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtyltvdezn.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gtflunsrco.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtgwtcruat.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gtzefbfmih.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtyjjppmkv.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtcmlddcln.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtsaruwenq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtkiqhxlbz.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtoqafgdhi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gtyaykzmqn.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpmisrij.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtrperirak.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtlmecvdoo.html

[Q76] 按天统计
来源：http://dali.cucudq.cn/Article/details/gtvkdhkodl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdavduzp.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gtjfcnxtnp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gtmtitgqra.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtvjgvgtal.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gtjfbcwoun.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtesmrkqtv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gtmgrihswb.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtuufzivdc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtruncfojc.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtkhjjuiwg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtjtsitvqk.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtqkqeqitx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtvxtobhdw.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gthzmusinr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gthscdcrke.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gthcjtxnvz.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtnonuuidw.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gtjoldhzzy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtwmqsgvul.html


<!-- 参考信息 -->