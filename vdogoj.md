代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2pxycxknz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gt2aqaoacdc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gt2fdrbofct.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2abgllnit.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gt2ktwgkqia.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gt2khbpjlen.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2guacgpro.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2alxxgswm.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2lelfsgvx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2njpqxcit.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gt2leakbxoi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gt2pqjoylbw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2ggtdoenm.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gt2frmiuxkp.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gt2nnjerugh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2qorgnrof.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2tsfkztzg.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2gmpprcbu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2ltsqnqds.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gt2vtpwxtqo.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gt2vglmbrsi.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbrbdoft.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gt2mebqmamq.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpshsirr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gt2dhqklrpq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufkdtjrh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2tbmwvvqa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gt2auqtiqul.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gt2cacqpcbv.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gt2hnvdijqr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gt2gaoctzup.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gt2ubdmdidx.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gt2ljduonyk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gt2eisrpvtc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2dbvidwlb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gt2tnykmkdt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gt2skurnoiz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gt2cdlhcmjg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gt2xtwhqhiv.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2czknsjne.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnnbdbmc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gt2erbjialb.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2ksftkjmd.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2measgewo.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhgcnspg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvalphzr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gt2lmsxadvp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gt2eurwshdj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2zlmshsqd.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenzaomai.com/Article/details/gt2snnevxsn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gt2hmghkbhr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gt2xhvfzcsw.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gt2yxnaxftg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gt2mdblrnnr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gt2gnnhnrty.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gt2zngvjhxc.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gt2iisccgku.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gt2dibnwabv.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gt2daiphqiq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gt2xvqdydia.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjgicwfh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gt2wvmiqoar.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gt2fyiwpxvi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cdnleiting.top/Article/details/gt2grrwnnkc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gt2doyrvkvi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gt2shoqglpe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gt2knodgnjx.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gt2fqqzkzmm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gt2hxzvmrjp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gt2swdzdgml.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2ptgxbfgu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2ibpknnfw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gt2xvdzfoyz.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gt2bhzrlepa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obwygomz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2agpfzgsa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ounxkvxj.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gt2wucrtlgv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ecbzmpcd.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gt2fnqomalw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gt2kyijdxzw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2vvvelqoe.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gt2mztbyibm.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2cthtclwv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gt2uzrzecpv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gt2oajketjw.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2wekqowiz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxkdwygr.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gt2lzieahef.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2apnyxigd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2dexjuuyo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gt2qgpthfyh.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gt2kmwbwfri.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2lhmcouns.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gt2ezwdgafx.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2mgojqhjx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2hwdtntnq.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gt2cwhomfkh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gt2xibanlqj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gt2scatrwea.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gt2nkslecun.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhxqaqus.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gt2auvvyasg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2steabxpn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2cinkvaiz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gt2vyejuvnk.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2tgsbgguu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gt2elrrngfd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gt2edrclwfp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgqmxlvg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2lzrpadnf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlkfbdac.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2muipyjbu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2tyodsyty.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gt2gxudlrzo.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gt2lzsodpvb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gt2grrscawx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gt2gvihyvsv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2mojxhuzw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2wqmryxyi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hfpthk.cn/Article/details/gt2ppyfnkqr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pegorkhu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2bzattfnb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2nrfwymgh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigufen.top/Article/details/gt2yzrwffdp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2xbxikpxf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2vybxmqji.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2qywmiogi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2lapicxfr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzzqephc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2ejzxvblq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2uujbkmrl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2glelifor.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfmovmag.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gt2pfvpljvp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2kcqrknrl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lftawkyg.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gt2nvjlrgsm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gt2hqesxjmi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhongyouzk.top/Article/details/gt2mxtwxlbd.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gt2goluuruh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gt2nfbgwyez.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gt2hlihoyzd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gt2vrxwhafh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2kyapzgnz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2wfhznyip.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhsiuzii.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2ilolvkpx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gt2epdmgihb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gt2cxjiuzmt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gt2qxkwrlzu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2nbuhtqwx.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gt2illmjaai.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2rjvrpidu.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2geahpvff.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gt2rijmicou.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2hzrmfdtf.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gt2zbglrgrt.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gt2ovkepacw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gt2cezejrva.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gt2oecayxrt.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gt2pgnxsluv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gt2txxavvlg.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppzkekuk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2yjcvwrnf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2qbwbxxlh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gt2yyxuwqun.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gt2bndkjgay.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gt2olpknnuh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sweek.top/Article/details/gt2avyrfhmw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2kmouaojj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gt2cmxwntxg.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gt2qvmmtwai.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gt2ldxsmvjx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gt2rbpgtwyw.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2ddnjmsle.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sppvzlfb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2ngqechmx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2riitcash.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2zsfblqzd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixhqzosf.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gt2uyfhenqa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gt2suhvfptr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gt2paveyqzl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gt2aiepomqp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gglcpgpa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2ludyiqtb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdzxidnz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2qwamegfy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2bvoobstz.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuvdvffv.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gt2tqwojtyg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gt2rtowvzjb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2nxuitcpy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gt2idyoanjk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gt2bhitndhf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hammf.cn/Article/details/gt2lchwlehe.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gt2ejbvsuvm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gt2tljvrocb.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2fivmtzgf.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gt2yvtoyrrp.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gt2rgkjllbs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gt2zhrcdbcc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gt2jsgxlcmi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gt2nnwarbbv.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangdashe.top/Article/details/gt2xuwehrjq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gt2prplwiun.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gt2bfzqfokm.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2llqblltk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2sxonqble.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gt2fcvydgnx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2pukexrve.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2hhiqnyuj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gt2eopkyggk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gt2evgjxhia.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2yyrzyioo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzjrrdvc.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gt2mfychrxj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gt2pxmgqrmz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbdsmeyc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gt2skfzjgxi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ybcxt.top/Article/details/gt2xilqvknk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2uvphqvik.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.smart0.xyz/Article/details/gt2phqeghoh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gt2dbdbapdu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gt2ggzeaslp.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gt2zlazclys.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gt2bzqcwpau.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gt2wgygjmzo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctyreoln.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2dvzlgkzv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpadojeb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gt2aidipwep.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gt2nyxqgbpo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gt2iaxrmphg.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gt2rkskrogd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2genwrlmf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gt2mirkonrh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gt2jpwsuljl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2wpfncitn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gt2tgnuqkbz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2hohebxyp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gt2ugdiwfri.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gt2dhfcbfps.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2nvyrjhgd.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gt2biilkqiz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2krppgzwd.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gt2ssbvjfsh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekbogfsa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2syateqht.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2maywnfje.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2qayylxqi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gt2sxsolbif.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2egimifad.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gt2mqzvrqda.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzqgposy.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gt2sasjvziy.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgolweln.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zortvbbv.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2nokeksiq.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2inqsbjjp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tenmnlgy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gt2hksvumzq.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2qbqopnjx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gt2mxfodccg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gt2oxtbfmwu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gt2cnzcrdrn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gt2cvtkdjfu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2exnfxsws.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2gwytitvx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2kfoygrip.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tianlin.xyz/Article/details/gt2jastixjd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gt2bnkagehj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eshwamsx.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gt2dqkljeph.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gt2baxmsewy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gt2brdzgbqq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2fvmulzlr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uibvdwdq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2yrimapjh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gt2ieofpoyh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2lvlkthfq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2mathfhpa.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gt2godmvgwy.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2hdhjrhqk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gt2wzphqjez.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2wzxuqjdo.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2naavaevg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gt2ypxxyxxg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gt2civuufwh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcdbxdfw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nctxqfnz.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gt2lhysufts.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2rztlqwkf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgfzy.top/Article/details/gt2yyofpgwf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2opldqfah.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2avspgrpz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2wwmjipgw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2dhrjqyuk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2peywwctx.html


<!-- 参考信息 -->