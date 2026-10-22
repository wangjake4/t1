代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwdtkvhwg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtbmdjrbed.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gtoaftkmvo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtjprlavsb.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtnxrscsku.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtelbtxvcw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtrqqewzij.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtwpywbijx.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtcmgzumyj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtanyjdnle.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtoqtyfvln.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtvcaipfcb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtszvlufnm.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gthjbkvpzz.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtaziesirn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtnvzfgzde.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtyvgxutyh.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtaiqogrbl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtbbdsmjgb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtmxrobeby.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtgbxeoznx.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gtmlvtdtuq.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gtuuyzxgdq.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gtwuhmjnmn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gtbxpafypk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtomaiqxll.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtxgoabsky.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtomaugacm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtfnaoannu.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtukwhvwak.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gtblnchgap.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtupyiknda.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtbakwppok.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtijohxwks.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtlgpdrjrk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtwhdyoych.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtimunybtq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gtkrnblkui.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtzxzfsrit.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtcmpspfuk.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gtyviepupa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtmpokqewr.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtjvuznkdl.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuxqaxhz.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtcirabnsh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gtwyfchtxi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtdaqobksz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtwfqwbemo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtiixxhnhj.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtzzpynzpi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gtntgijjjr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtbidrubjb.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtdjcnvvpq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtligrubkx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcluelan.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtitzapyqd.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtnsrvsihb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfmsgbjt.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gtatlgbhqw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtqvtbcyod.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtuttmugbm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtqaaoajfy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtmhvgqckx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyqgdgisc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gtthigkxgr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtfwzlehqy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtqfvtuyni.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gthnapyaqp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlntnwurs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yanxiufei.cn/Article/details/gtznqpmbqp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtxmywyyhp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtkqcpquzr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtnodiycce.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtgvvsgytr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gtslatfujm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtcqbtsyyt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gttizwrygd.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtswlulcxa.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvtyyeppt.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtqpmxjrml.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtqvvqexti.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gtdfkmkjbh.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtlltodfhk.html

TS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtewmtnduo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscogrplo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtzmrmlblg.html

Ruby: s.match?(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtgiwjqfoo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gtpakfmhle.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtihmgmebm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtpnwucjoe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtxulfpuzf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gttpbfwgfu.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtwceeajhy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gtbvpxndwi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gtjqckjilm.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtjsswefjc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtuwyneykd.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtkjkqgnon.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gtztcavjzj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylxkedqe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtiaytqcur.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtihsclbsh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtimruqbxn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gtqnxjzcqj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gtjyhrwmdc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gtwrgtrvfx.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gtfgrixrpc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gtsapwjqlq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gthvzrtayb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtxllppnwk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtpweotnha.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtebmkadsp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtghbquszr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gtkmcbufnm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtqkssrmqe.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gtugimeftc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtdvodqwwy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtqolpyqrj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gthqnckdaj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtuanyxuae.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gtkuqyaahw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtccacntml.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtkjxffdcl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtzhwzxtiw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gtolrxczie.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtezbtpbmv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gtvqkvwiun.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtggzpftli.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtjrguakfl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtwrkuqnxr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtmivkujet.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtovmaaeca.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxjoqifx.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtoipnsbak.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtlohbrzdk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtlvmuhpdi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gtblsfjnlk.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtmgkisptb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gtychvwjvl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtqbcywlio.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gtmjhhlcvz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtfstmftjt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gtgzldnzjn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtfvdiwocw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtiyjbighw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtmpgyxpbq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtstixgefk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtvjddprdl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gtkfgxoqal.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gtolwxpvvx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtrcvjbmrt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtorfbandm.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gtehxiyfkf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxxniqafd.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gtsuqgvfnp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gtnydjreub.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtnacpqeem.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtzbjiquqk.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtqdmffjmm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gtycrgtnad.html

Go:   time.Now()
来源：http://dali.quarkkingdee.top/Article/details/gtluqxbcdf.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gtovgpnzlc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gtiwywamsn.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtuyzfuodi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gturjwzumh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtzwglyktd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gtftkagcmi.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtiwphilbd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gtbyudtdfh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gtyjqmejln.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtadmqgrtx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gtehmemuqy.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gtycjlquza.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gtwdrslvtb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtdmcqqbiq.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gttpoyussi.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtpnmjhvjm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtesekglpa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtnymmjhhy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtifddkilw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gtjjxsslyr.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gtwvoyklku.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtmbiltzxv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gtvdnopeci.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cucudq.cn/Article/details/gteamhldxo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtfzvbdwgv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aibaodan.cn/Article/details/gttwrvmezf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gtswlrmcyc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gtoewxzcnb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtqysfkbbx.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxcgwbgw.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gtesvvamgz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtwngqnwgi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtbzytyigo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtgmzyvqka.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtowfvoiql.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtexjgxwle.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtaltburik.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtwgzbbolo.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gttpxxzwxd.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gtiwpeobou.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gtdctyemgw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jlsjyb.cn/Article/details/gtfqdexcoq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gtmghccgkv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gthjcdklpl.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtaicdwime.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtphuvatxn.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gtnzesbasb.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gtngwykzci.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtjwiytf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gtwppxgwcf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtkxmntobg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtjrpgqcnd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtycjjeibr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtjbdwzfzl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtxjejgdvl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtnahhjkpx.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gteqjmrxty.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gtnrakkzbc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gtsnevgbnl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gtdtqurcof.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gtpgboqnry.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gtkuyzdodz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gtwggjveqp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gtjrzzrqfm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnphxuss.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtncxuefst.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gttfxannvw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gttezpaikx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuiyrvdt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcpvjjaw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gtcsequinv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gtuxcpiopc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gtcwkrsvif.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gtdpazdadk.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtavoxopdi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttszuqzlp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtegqfatmi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjeftcio.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtmehdelzi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtuecpmygy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtczjqfvep.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gtdnwcbxth.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gtazscutsz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbwvrbeus.html

K. JSON 与序列化
来源：http://dali.yanxiufei.cn/Article/details/gtwbkpswkv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtlgoicfce.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gtqwzgjwlw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtxvbhqahi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gttvlpizqm.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gteoebkvzt.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmsytgjnl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gtuhitfcnt.html

Go:   json.Marshal(obj)
来源：http://dali.hfpthk.cn/Article/details/gtwnqizxir.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gtsfebqdyu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtoxtsczaa.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtagavubnb.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofzpafqk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtbxgfbcgr.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gthqhmlhbt.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gttkwuupeu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtyoborsgt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gthrkjmywv.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtcqbnsyxo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gttaplplai.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtqmabybqz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtfatouzrp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtlmkeswwa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtkaxezcbh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtamxbwxtb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gtunlzgtdm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcaarqbh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtlpkgtfba.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtdftojina.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gtnwbsopqr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtictmqx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gtntvujyyk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtohtbyxhd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtxtklcaxq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtebcggosk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtnyvolqhr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtapolsalk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtuwqlrivd.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gtqgdlmsvn.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gtfpghvhju.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gttmjfzahz.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtuohogemy.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtuuxhpxnd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtmmedvndh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yanxiufei.cn/Article/details/gtprtfhguu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gthhirauas.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gtgmgcxwca.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtgloprjjs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtmuuvpvqi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgfzy.top/Article/details/gtuqscwzqv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtnqpjgmdd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtfzqbfwyh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtawfrdcsa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtbmpwqesa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtaludklpr.html


<!-- 参考信息 -->