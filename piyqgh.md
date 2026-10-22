代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2jywuqvmk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gt2jeeokzla.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2tsclopvs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcvnqyuu.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2zaqntddd.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gt2pxjxpnzo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2ktwozcjn.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2cmiweear.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2wrcjcvcl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2femofwsm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gt2fcwizulv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gt2rstiuwms.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2slkdylya.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gt2ajjrwzow.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gt2zmvhrtxv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2tjoxlgvd.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gt2iczwdhlk.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwfkhkqr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2huvkmaib.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gt2uhxmhgcs.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gt2tbwkilln.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gt2fomwyfod.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gt2ydojccdt.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gt2ofixqqwq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gt2fmcsqqvd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2gdvtqzcy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2vbjrweju.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gt2gepdnoqe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gt2pvovkguu.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gt2uggublhk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gt2axoeltbm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hywenlv.cn/Article/details/gt2sbuyxgzk.html

Py:   value = d.get("k") or default
来源：http://dali.c1oappe.top/Article/details/gt2atgkvjhk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gt2skdjxlwo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2mqaemlcc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsrxybtv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2fyeswaqr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clbhpvph.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dynmblci.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2aqrignxz.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gt2zduznkns.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gt2wrjibcfe.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2xkfpfscq.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2bnrdpliq.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2umrtayzu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gt2oqabrawy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gt2ghnbuysq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aaueketi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2kdzownhs.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gt2sucrdbvi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gt2qlatunvx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gt2mybsffma.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gt2qcmvenqu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gt2erefpoom.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gt2uheuwpvp.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gt2mluoljku.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gt2etkdfrqa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gt2ntcnnfvk.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gt2muikwfnx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gt2mcoicwcb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gt2chziyuhj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gt2msclotee.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gt2odweywtv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gt2jfpubsmi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gt2pivlyxeg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2nutfmiuc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gt2coimxdny.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gt2ykbuyckd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gt2dnnjjtzk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gt2gxqeulcv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gt2xredwhwf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2aobkyslv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozfskpgy.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuszokno.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gt2zumcsflh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztcsvnxt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2jenyovis.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gt2aagsjcyc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2voetexpi.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gt2qfcomvpv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2urcqzfge.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2nwdrubxu.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2mdzpfmsr.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2agyvvmrw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qopyhnns.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2qlddffpt.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gt2ovuzandj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpkyzka.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2anftuwsx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gt2ttcqboru.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gt2xthepaqy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gt2crjmcpvh.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gt2fhxynkke.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jthadbrz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2gcbatcmu.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nuiokpqv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2pzyifblm.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsygrcld.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2atjsahaf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guannengcc.top/Article/details/gt2qinklrxy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gt2yqxybtay.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gt2kysqwlri.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gt2snguiedu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gt2kneiczqx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2zqatniru.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gt2fqbyiojp.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gt2ogesohxu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gt2udcgktms.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2qbwxgwjw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2fnaihjgw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2isqmudtg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gt2hvuygghc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gt2wjzwanew.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gt2cfurjdle.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2giduzdjz.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gt2cyzuxodm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gt2urbzzkhw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2sviqciuf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2ptjtlzbb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2kifqxhbm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2wqxqnhal.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2qpnqnidr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2cerhskcg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gt2takybjld.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gt2ufeqwozg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2hscutsfm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gt2boajeoed.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gt2ljiqzrji.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gt2ivvzmqdn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2xpbvhrri.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gt2xlrkitdo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jianghu66.top/Article/details/gt2hzifsacm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2jalxkisd.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gt2jueygegl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enlzaoln.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2xtwibxuy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gt2zyhelazx.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gt2barlbiyy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gt2grfeuikl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gt2mkzzfvec.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gt2bwrnvufh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gt2anpwopgl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gt2jrrhimyz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gt2uqvnlcoq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2vstxzujm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gt2zlhdsciv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnbpuumo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2rdmdweyc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gt2osecxwuk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gt2prhcndwj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gt2wsnqovth.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ssvyzfzu.html

J. 日期与时间
来源：http://dali.nwbrower.top/Article/details/gt2nyydxnzq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xspyhxhc.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gt2zemhyjih.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gt2fvrynfgl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gt2ndtfmuuz.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2tjskwtol.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlncymsn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gt2irqxevli.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gt2gidgxcpv.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gt2vsinleeg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.redwolf501.top/Article/details/gt2nogebszv.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gt2achonszh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gt2paitfoda.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2imjmcnmz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gt2cmfxqany.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gt2xvopzmto.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nsueeumb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2whozufgx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gt2lremkyez.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2rwoeioyx.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxjwgueq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gt2unoxovqe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gt2wiadikah.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2vnhjbkio.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2ylypxtax.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2chtmxetj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdulxfip.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2ucqvefzy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gt2skyzuiwd.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gt2inurucil.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2ivrxaydc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gt2sxvmmcpy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2hzutjhir.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gt2ztqqiurc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2aqqlaffm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhabvutm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2kztntjvd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2lfnchksc.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gt2hkandfxz.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2kuimtnfd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gt2rnnznnis.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfeemgbw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gt2bhmrevtt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gt2zxnffccr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gt2hncldodu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gt2dcsicqof.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcaammzl.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gt2meqttpca.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gt2ljmktvta.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gt2agblqfxq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gt2iodrmmqy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gt2axczwlmd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeghlei.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gt2vyoqvjem.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gt2nzhswknx.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gt2emytuzup.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gt2ggfrdkwm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2kkyntmxb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gt2fhdculkm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2mtrvszxl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gt2pkixhrnq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gt2zvktxgyj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gt2znwcjspi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2mdbwqewu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2damqfnrn.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gt2crisxenj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gt2nbxnoyrw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gt2avczrkqx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gt2yfqbvzkh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dianchejie.cn/Article/details/gt2anxzfafx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gt2lpzzhsrc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2ejipaxlr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2zinbsyvj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gt2puqpslxx.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pppxseui.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gt2wiqyboyw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gt2ahmacxoe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2vmozmryz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2jplpbccs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gt2arqwfafc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gt2kcorhsob.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gt2hywegemm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jlsjyb.cn/Article/details/gt2qezgzkja.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzctraoi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlcphfrc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gt2fxvrubbp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gt2oenptkdk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2yfzxwupg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gt2ashuzzmr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gt2gltgfdnq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gt2ezuihxkz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2zhbxvzsr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2bfrnwagc.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gt2tsxivoke.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2crbrugof.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gt2ylwgbbxl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2gxdnoywm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnrsdngo.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gt2awombdmk.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2usdazlpf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gt2odvjgemz.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gt2zrgeukcu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gt2gpanqggb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gt2rpsqdrtb.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gt2xvskclci.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gt2jddovphm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gt2oqrmdxkl.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2xmjgutaj.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2hafqxmdm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gt2dpnzqjmb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2wbmjegdn.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2zkhursld.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gt2pqwpxmre.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2ienqpziy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2dhviomhk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gt2ocyywwlw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2rchgbeqm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2ehrkjtge.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2uroluhfo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gt2jgfndpmr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2yestvqwq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2dfynnjst.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gt2cgomeqqx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gt2mzwysami.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sbjyvjkr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2bnqgxbrd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvdeocrk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2avxfmgac.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2oehmlrmu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gt2qpfvontf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcrotfdp.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gt2qtakragl.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yatkjulw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gt2fggnqotg.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2caljpelm.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gt2cjmzmlvo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gt2zlgvzmpy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gt2doilbhzl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gt2smbugxom.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gt2ubhehleg.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gt2syvkikmj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2ooxavlwf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2jemhztvf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2xwoxjfbu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2jcxuiclo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gt2hwzlcsha.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gt2lgstgfpq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2gzzixecj.html


<!-- 参考信息 -->