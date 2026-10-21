代发 wailian999

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gttbtuqcqq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gtobqflxxm.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtoiuzrnib.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtbclfiwly.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtrykdycrh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtutkuyaed.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gtcnrzbnxk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gtesyzauhv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtymghylqe.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gtoyhazkvl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtimtqngqg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gtfcbowxxg.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtfqxilxhq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtileukidt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gtxrzffubx.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtkevewczm.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtdcwafhty.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtytrevmam.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtupeydtaj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gthozjmwqx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gtizvapzgu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gtnjefjjia.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gtvdznusht.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtiqyrhiqd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gtparaofse.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtztbfuvqi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtjioccems.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkuflsux.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtzawzasbb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gteppmtvdo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtdfcfekjf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtnetpxxqq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gtyutmwzoz.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtvjwmmlsx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gtljotwcnn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gtqzsejmel.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gticpykadx.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gtefhixniz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxeexyqve.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtaixyzozp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtiirqvuqx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtlenvzppe.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtjaurglff.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gttafjaivq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gtuwuxfkax.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtgstoqouz.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtjpkxcriy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtpxqbpgea.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtcmralviv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcucshtd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gtqpihtkpf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gtblmxqicm.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gtqwiuvkml.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtnravspne.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtrhruxsal.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtsnjfghey.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtapkmkafn.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtymsjeyre.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gtzzxsnzse.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gtbhhpdpyq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtpbsabezt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtzhxnueim.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gtaybosbkj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gtdxzaajwm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gtphponrte.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gtcznuwnux.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gthvebvrmj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gtcqztlcbs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtpocqvvaq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtaobtetwc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdltsadp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtwngespti.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtyugqxqaz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcmzpsws.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtiejxnvin.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gtxtgwotvv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtwplmqxdk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtlyuopeos.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gteizwzfpx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtqdgyvbug.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtstkxvplg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gterpssvvk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtkvwajeye.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gtdmkdhpku.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gtgtqxnorl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtrvacxxmp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtykolzpoo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtvmgaiear.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtnqgemwsn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtgnvlargj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gtqghcrfli.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhongyouzk.top/Article/details/gtjfwxvpwa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtxheavryh.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gtyeeedhpl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgrodehw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtptrdonnc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtgxkisrvi.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gtkgetguhv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gtqzfzcumo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gtnbxhvizp.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gtvhgksznp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gtxbqzybxx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtfpycxmdx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gtvvuusdxb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtoidvdztb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtndsuoosm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtzmbxwihm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtvjexmvpg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gttmwrpewc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gticaayube.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtxoxgyxki.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvynbhgoo.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gtpxclpqqn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gticsrigrq.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gttotajohl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtezfjudgt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuplleky.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtoxbccnwu.html

TS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtrhxgwlba.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtwgoygqgf.html

Go:   time.Now()
来源：http://dali.ivvv.top/Article/details/gtfyrcepni.html

Ruby: Time.now
来源：http://dali.nanxinkj.top/Article/details/gtiobufvag.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gtmlbotmby.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtyltqpsqc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtmauthruf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtduwcvuph.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gtmlyvbkzi.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtwajfgbdj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gtrxurzrlk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtbxeiqwyh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtfrxrssof.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gtqgebjsjx.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenowytkk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtpdmbccer.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gtmqswtixq.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gttlfiyfdi.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtaqtrksax.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtidgusleb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtgqtvqenb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtbbkbboad.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ivvv.top/Article/details/gtodjsdefr.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gtkqeuhomz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gtnydtzthq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtyhazwgoj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwjdtuxo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gtgmvxygrq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gtcsnbunav.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gtyvwhzoxh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gthrgqpmhg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtxcsjvfoo.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gtlbcidlsx.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeztfkfz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgfzy.top/Article/details/gtyognbmeb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtgjryvluk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtzyeyodoi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtqnvfsbqa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gtgpcsrwxz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gtvkrjssjr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtvjepnpno.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gtfxdkdqjf.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gteiacgsry.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gtotujutdt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gtifwdqcjb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gtegmkjwbe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtzgaverhz.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gtdjhxvukz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gtpuawqlig.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtkzbjamjo.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtkdfdsnai.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtexxipihm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtojfjndxm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtrnkhptjo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtassrheza.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtrmzxnrnz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gtoleccjlp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtqexjmhnp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtzffyevzw.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gtguxtgslr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtbyvqyyfb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtaljtwvfz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtukpbhnmp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gtjyrfnbvj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gtydedaxry.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtexdspyxn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtndheahzh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gthrhbnzrv.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gtteaxkyik.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtnnhzwprk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlclgwihd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtnevktrlp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtthokjnwh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtjndkveen.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gteawurbem.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtrtqetbcw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtimrosnmh.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gtobcbwtrn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gthnavvejz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtvboahdva.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtqdquwjlm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gtcycsmrdl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtrbbuycmp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtxmhrlvbf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtbrytkqfl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtrmhegbsg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gteincmznp.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gtlaskkpnm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlyngmqbu.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gtqystndft.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtrtclkcvn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtfctjokdm.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtirwrosvh.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtbhxapmpo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtitixazor.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtevfodncy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwnclszp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtynipgunp.html

[K02] JSON 字符串转对象
来源：http://dali.aizwys.cn/Article/details/gtvbaxhabg.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gtqbvjuofk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ehwqpu.com/Article/details/gtxkgwclko.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtygfkvsbo.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtrvzrsghm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtyytessjq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsrztuyd.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtzffdlfgf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gttshrxenv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gtcyusekhw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtantpysyx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtnwdyhpra.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gttrclbniv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtdmpescqq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtqtanrdij.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtagcdnrqr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yongpay.top/Article/details/gtyksisnnv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gtolpyddkp.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtjprausbp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gtoludpkct.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gtoldvwizz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtdvlmsnex.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtabptpxee.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gtetazzqvq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtwengkyyk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtfkkwmlkw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gttlkrvtbz.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtuyzwfgiv.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gtelgovthb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gtwjlykwbc.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtuplewslm.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gttohafgjw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtydouitii.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtnvggynzl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gtfukzsuoa.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtsdycbirz.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtbpcgjzlg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gthycxrvxt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtvidshnwf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gthjdmttld.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtbzlwidyb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gtdjerpjrn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtamnpawuj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtjaztdohg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtxedewbft.html

[K07] 进制转换
来源：http://dali.hysaishi.cn/Article/details/gtspiljcly.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtblodfaio.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gtqfxsdpcv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsergihst.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtztnpxywp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtwtcpjjxh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtbkpifzwv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtofzswcvb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtjramrzhe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtszsvfmqz.html

Py:   pickle.dumps(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwtgvtox.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtgtxbumss.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtngqgiyck.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwlnqlxq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gtqsdkfhyl.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gtdzhehsqp.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gtlrccvkog.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtaofopkmx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtntwilbhs.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtwfoimbpi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtacdagecj.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gtvnsxgdkz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtyhfdxyww.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gtsrwkcubm.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtdmafrmfn.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtyuhceise.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gtoabcyoyl.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtqhnmcnhd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtdeulkbah.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbtvzteb.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtlhijdhbk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtzvqeuoio.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtswlwbpcy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtvluwtbiy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtyadvpris.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gtlpyrlrdo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtdwjnrkpi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gtxkwhujsm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gttxerlwpq.html


<!-- 参考信息 -->