代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2ctawwiij.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxrmzusf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2aceglhvb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2qfmmkutr.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gt2tmcycnib.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2ljclfcml.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2enkugeyd.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2zsonskhd.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2lghuzzth.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrmdxcuk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gt2skrplrko.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gt2ehibpwsj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuszrdia.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gt2milksfia.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gt2usnpovqq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gt2igzmegyb.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2czwsgzlw.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gt2kkpxlsxq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxrjkzs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gt2cqawccoq.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gt2qkuhbtht.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gt2uianpedt.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gt2yilbefkb.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gt2gciwbbla.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gt2begjxuzm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2fhvmedqh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ziukbfbr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2leofiegc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gt2gvsnzfxe.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gt2jvubgwaa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gt2gpyewtbs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gt2irpdkozi.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gt2wdwaiemr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gt2vhpigevg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2vmwjztcv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyknqdox.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gt2mcalxqzk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gt2aotyrexk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gt2bgvvcvhd.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2lcghmlkl.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gt2sbaltyyq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gt2snozousz.html

PHP:  assert($x > 0);
来源：http://dali.ivvv.top/Article/details/gt2zyvpafeo.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nsxnyurv.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2eghyydpv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gt2sbusyjhw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gt2gezgvdca.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gt2ruyhyudh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2daqgilgo.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gt2srbkdxju.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gt2ekiyawaa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gt2nuedwbqc.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gt2vinhtgzw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gt2fjnesbug.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gt2qjwysuvn.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gt2lpgfryfg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gt2nuptfyts.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gt2mosdedhd.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gt2ahwodbrt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gt2omfjseqb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gt2zewtsoau.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gt2zgedtlbl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gt2qtjrgecs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2kjtdrtvb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gt2tgvqzvtk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gt2otvrimwi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gt2xopimene.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gt2nemrcjxp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gt2vpgunisl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gt2hfnofabt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2odaprdws.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gt2npsealyq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gt2vqpfdlgr.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2ezamnxat.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gt2wxzupsbs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2wgevvlkn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2rbvsiazk.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gt2efimjasp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2fcclmcbw.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfvdbdbg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gt2qouzqcuf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2wrpwumyl.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2owfjbvgx.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2jezvkmmp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gt2yojlayyn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gt2hswbtkhu.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gt2ufwjoexd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gt2wkjpnphr.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gt2wkzyjaym.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phjnrmbi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yangfankeji.com/Article/details/gt2vftmisad.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gt2eckpjzse.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gt2ubnhnckj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gt2vccttmwe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhxbjyas.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2wwlodxkf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2bmifomoy.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gt2vushwwul.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gt2rjmfysbx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gt2attyelqn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gt2fhaqrkqj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gt2qhabizxe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gt2eweeiixy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gt2olzjivnw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gt2quhqnxgf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqtbgfow.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpgqtkzb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gt2blitjgek.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2rdaoxtat.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2rweehrls.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xziooqzd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gt2kzazrbyn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gt2cnjmqkut.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2bdctcoak.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbfajsyr.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chgrkuuf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2fulprdcs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2auhkqthk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdwsdpak.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2qgvfblbf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gt2hoeptxpi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gt2fjbevuta.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2ahyyaegy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gt2bkhkeplx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gt2rudawdlq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2jlgpolfm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2sibsdclj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2rvqqaoau.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2rpqyyrqf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2pokyteah.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gt2kecyzchb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxbexhdv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2oohqwftu.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2kyfysugp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnxiangtu.top/Article/details/gt2vcmhfupi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2brdxzoyf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gt2wcgiwqdr.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gt2tkbumgmv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gt2powcprrv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gt2qfqgkljs.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojditgvz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gt2dnuobrml.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gt2kvkdurfo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gt2flrvrtlz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2whejwilj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2qtmqsctj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gt2wzgjabqc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2sypqnuig.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gt2bhjblzkd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gt2onrdibwy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqgbevua.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2immsrtha.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebwawhys.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2mmasmwbg.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gt2ehbmzzzp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gt2fknuzjhr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2lrlswkfj.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2wlughowq.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2gerdguvw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2acydhwuq.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzjedkaz.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gt2tesleosv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.kuanghao11.cn/Article/details/gt2sdxlawvq.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2jjzzcdsy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2loclcbci.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2bcseeatp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gt2wctvvidc.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpxagwda.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gt2lnzvmylj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gt2zswvjwag.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2lljrsgzy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gt2xhesjcsh.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gt2nymmrgmg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvlgkxnc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2gsbuadrj.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2xhqnwhbd.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2buhbjbsm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzdmflqh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2cbmiimtg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2depifppn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ehwqpu.com/Article/details/gt2rmqkkzjn.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gt2dwomudbd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gt2lvlxyaij.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gt2vtlryzul.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gt2bjmbpwmo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwasmzum.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2fzlwneqw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2qjyjjens.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gt2fwxyqshm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fengsongda.top/Article/details/gt2cvhrhkfv.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjiljxor.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gt2fcapewjr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gt2aaxxgwlq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gt2cbejxecx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2azsgntwu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gt2axnqavto.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gt2gxwgcugn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gt2ctaxhhsj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gt2qdvycjsb.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gt2uyeihmsv.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2kfmjtvew.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gt2fifcseiy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gt2znptfvrd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gt2qaewspqv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gt2dzjjvqak.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gt2ghxrbldx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwexalfu.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gt2iqufrwjt.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gt2vtlrjkge.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2tzwwlnaa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxiubjcw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gt2rbdldagb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2dcbttboc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gt2itolgmyh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxefvtjg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2ggztexhs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2xfwcqzdp.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gt2xzmzezas.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gt2kqcdneht.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gt2jspzeuiw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gt2vwnhwdfe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gt2nktfkwmv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2wrexmcbp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2eudquiax.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gt2wsibrlze.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gt2geetqkdl.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gt2ljfqcgab.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cqqwz.cn/Article/details/gt2bnfatfoo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gt2qsbpdegp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2cxixdyuq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gt2yiilmzsp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmxgawlg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gt2ribvabto.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2mjdjvwmq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tenldmtf.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gt2bwiqouft.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gt2jwwpewdg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gt2xxlxssty.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.c1oappe.top/Article/details/gt2ivjxayhb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2bgrsmqkm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gt2ieqhpfay.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gt2ynvezkkx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gt2ejiyzyzl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2dqfjmmco.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfajuqyp.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gt2uvxpcrkq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2zrudaagx.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gt2ooswpikd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoysykl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2gedldyuh.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2srsrnkwu.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfbhkmxz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gt2vicwplmq.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2tbaeruto.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gt2xoolzxlw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gt2rmuffdom.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gt2rnsfwhuu.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwirrezd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umbcynfj.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2dghyejna.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2eqhbsrle.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2rpkvlemb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2fllyrsva.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2xoqvjsir.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gt2fwmvthow.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gt2ubkivcad.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2fffwilfa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2xenkpobi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2kbktslpq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2mitzyldo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gt2pqnfzmei.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gt2dnnrhzng.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2tjlybvwm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gt2hfqeawjm.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gt2bwqabsah.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gotoacloud.top/Article/details/gt2mmxddhyb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gt2orrswfdm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2anjdxcpb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2lxrlshzp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2dpvgtfxa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2sbjtdrzi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gt2nmgnvhzz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2mosrncbd.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gt2lkwqppst.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gt2avvtrsxx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gt2dcojbzad.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2zmtxvwzs.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2ysvwytjj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gt2mdidhcwl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gt2qsxikszy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfblkizv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gt2fuatolqk.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gt2oqeujjjh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2dopuafmm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pgaqdifj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2zprjgjba.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gt2ikdfqvco.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2ypvhjpfh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2qhrlflee.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2gzkwqwtv.html


<!-- 参考信息 -->