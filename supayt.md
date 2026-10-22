代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtvoblgcpd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnvhbktw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtbprzgrvp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtxgzlbptt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtxrxgjevc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gtcelquzdp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtwupoehqr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtcovjgqwh.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtrghysjss.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gtubfxphsc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthukbouqh.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtdmrikvwj.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtqfikcqbx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtgqtwlpzn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtfvjxbesv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtfmxtzyiq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtdcbuklwh.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtmzdukvit.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtipwtekxg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gthizxuxbk.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtfofvrweo.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtemmjahyq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjbxnkkg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtzgueaubh.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtmiruvzxn.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gthcdimzay.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtdcvyrjrg.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gtsuzzsfra.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gtuetparqs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtdgwsjbyc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gteuynzuvt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttaehtppz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gtncapyugx.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtkqmblwtg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gtecwfeuys.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtgsucorcs.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtwjrqitmu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtdimjwubk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtmzipxxmg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtoxcmsesm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtjhwlxclj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtshmyddss.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtdkdabpwy.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtbmxyhybq.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtjovsamud.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gtztecpltx.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtoehxvhqn.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gttzoujqid.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtxbsbbqxa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtcedhvlsk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtftjihmsx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gtrjciyxzl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtejiptucg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtrvhgeokg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gtuklodzbk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtmpnnmjoy.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gtlonmejjt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsdshfuq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gtrynolpot.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehhqrldu.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtgewomuve.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrryttfji.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtmgjkkwzk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtlxkdmzaz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtlgnczwby.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gthzpdphcj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.0kj1m.cn/Article/details/gtrsjoxbch.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gtrqtcywjg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtmymajbzk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gtadqyevjh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gtukkajphs.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtocvkqkgq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gtkrzdhihv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gtfmotnqim.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtepzedioy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtphxfnniz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gthrsjhvjb.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gtqnfcrapy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gtjmbwkhyh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtmdufymuq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtldpmshrg.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gtiaqcyqkk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtzhesmpuc.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gtiosggmlm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtjulcqwoh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtjzricrsr.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gthvftnrxn.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtistqglen.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gtpnpozzgr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gtlpsdpihh.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtkamayckh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtrvtatxks.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gtzqmquhlh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtbhuiwpht.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gtaulvnkxi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gtbadkungl.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gthwjicteq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtwjsxjkvf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtcsmhnoqb.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtjhhookmz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gttyzxbawv.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gtgwpjevag.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtarlqdpld.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvisjhqvb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtagcxicev.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtquuuqijt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gtwmztolkt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gtbxttzlrw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtvjueytce.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gtjmcmnvur.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gtrxbocftd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gtdmlmijoo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gtknbumrwi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtahzpulol.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtffzxpyly.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gtvkdjuhrq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gtvwdgwdef.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gtmnkmnvwd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtmvjhraht.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gttiphpnjh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtiqfsgzra.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtvcrcbjdq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtdpfqsssl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtqnjldyvc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtyclirmub.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtllcptebh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtbflztjms.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gthhbrrhkt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtynpgbdnx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtwookdery.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gtlergexzv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtqhjyllpv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtqsiugwry.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtjmuqvesn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj202588.top/Article/details/gtmijblhkd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gtfraywvmz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtutxrxmis.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtcgyaikok.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gtxmvwkusr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtqezcezrk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtauuweozn.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gtfawzxbpc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtmpkawtcf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gtgnrcdhdx.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gtznwlxgqm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gtlwecxkfm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtbdothckc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtftnibrgm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtlzccvfkv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtwwxkfhyj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtuzuskfzs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtxdzhkxet.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtpuralaap.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gtopwnvtjm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtkzhadwaz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnuajkqov.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtnrqvkiqc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgnhivybl.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtbyixeucz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gtowvmmaup.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtzslzcvnf.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtsklgjzfo.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtswyzuqqz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gtnqlcnbkf.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gtzvfaetsa.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gtfuarsnpd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtznfflwwt.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtiabpsphw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtnvhynkzb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtcydtmrkz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtqugzgchg.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtsyuzbsky.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtjkftblei.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtenndyqai.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gtxmrzgxhy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gthjvojtuf.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gtlgqywltt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gtqjmlnvac.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gtnwsyzktq.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gttftmxcrj.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtitnqixnw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtuflvhqyt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzlijfdg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzkvlxpp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtiekqnlmm.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gttvenlmza.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gteozdlcfd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gtxozbplyp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtznqczjwm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtbnqwplzg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gtkhhshync.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtmevgjvoi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gtjnmpviqx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gtlpgybrhz.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gtsderhbbn.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gtpwkukftn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gtdddqvgun.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtfwuwbomv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtzjykrlki.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gtxnaeomou.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gzhubu.top/Article/details/gthonzgeai.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtqrnktrtp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtpcguuroj.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gtmhpbpozc.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtdiycweeo.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtjdhapsrw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtphbplkjg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gtygtsxduj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gtozgxfarl.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtzhnkhzuv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gtnxbnfcuh.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gtdeajljpg.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gtykaxxvxl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtbrfohhma.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnahcjttn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtwywwjqdq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtielvduog.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtotivhevz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gttgjxfehm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtoiwksovb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtyqjxibat.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gtzzmzocma.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtjvetheri.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtncqdsvdj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gtmktlinpz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gtuklmtano.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gtuphcmdcb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gtrxjirrus.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangdashe.top/Article/details/gtzelzcyny.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtgtpbipmf.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gtnoxwfjbz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gtksgtqwex.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gtgqytpjmu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtmleewkij.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtcnuwpwjy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtpozobfde.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtuiileaox.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yonumen.top/Article/details/gtpotzrimq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnqzz.top/Article/details/gtrbkejfub.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtcgqyzofk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtjxltkshx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtrrhgjkwc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gtjfmbhwgl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtmrcegoin.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtmurbluam.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtnafpuqev.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtsrivqzvj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gtfhukrsdh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtdmzsapra.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gtcztygpax.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttabixosg.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtqejtlefd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtxyuvvgbn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtuqbxzypy.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtyvvvlqbl.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtmzzyhkvz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gtkksirxdj.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gtepdxdcsg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gtswvzffxh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtbozctcgv.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gthqfkvpcc.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtkykuuskq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gtbpqgbjkh.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtwwrnxqvd.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gthofngfhh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtqlempqgo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtskjrfyej.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtomnyzfkt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtixfyocnp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtqxndnkur.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtpkxnswbv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gthkypcdec.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtxiwoppyo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfuwdqjd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtmsadlncs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtjsxgkmbb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhjtnvnn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.daxiang520.top/Article/details/gtwsssycsu.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtabpsrnwm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtplmjjflp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.feifeiyinyue.top/Article/details/gtljzsydau.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtmsxctjvb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzytexjjg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gttvngadbf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gthyyelhgz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtvudename.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtykmsfpcq.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gtobxjqowq.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhcnkzwe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtnxiwvvqk.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtsbkkscbd.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtvnwrjsom.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfghtjsc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gtxabzaazu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gthneypvzy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gtmtwjojzz.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtmdrrmueh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtovafumum.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gtowobnusm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtmxvxedrr.html


<!-- 参考信息 -->