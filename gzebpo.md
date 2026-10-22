代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gt2qhzxuife.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2zxiippwo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ngkctvsj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2qqzavdux.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2qtkhyzjm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gt2ljauwsls.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gt2heolbxui.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2pywvygqs.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gt2faldsxdt.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2acjaxuio.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2fnivtpzz.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2ctquxcdm.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjatuzcb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2scnkssvc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gt2uwkmzxss.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijlrivcm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2ymraubwc.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2okbedplh.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gt2dnyksvur.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2alydqblr.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2jsuiviwm.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2gppmyjgj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gt2hihoobrc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2vxjpqspx.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gt2oyrlrlno.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gt2rzvrptff.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gt2zepblayn.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gt2slfiopbw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2yfaalabj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2vcvxwkor.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gt2elpbbare.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gt2yvtkadli.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gt2ckmopaiu.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gt2urzhfwxb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gt2spnsdrxz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gt2prwrzqli.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gt2eqtortjb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2kembhzcg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gt2zmbsyeoi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2agsbqpmc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gt2dukzndvo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gt2wurttgfm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gt2zkvrjdxx.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2gavtokes.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqvfhvbe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gt2ycrqxcuc.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gt2yobpgfcp.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2sfugjvix.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2zfbnngpe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gt2zaklpjae.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gt2eswextsp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2avksbhni.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oepwehjj.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjheugai.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gt2ippjnsuz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knwjgsgr.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gt2qpbpadzz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiolhuta.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gt2uzjajeqq.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gt2smstrcjf.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gt2vtnnephc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gt2rxkvfrts.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxjshvqd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gt2isieccou.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gt2fxfpjazk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gt2qdtziaav.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gt2obevwybv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qykwrjey.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gt2ggsdpwlg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egmqgyii.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gt2canpgzng.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gt2mihtjfxn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gt2jdkxoazt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gt2flkfzglh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2ruybkfbd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2ewosborp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gt2kbggwttx.html

Go:   defer f.Close()
来源：http://dali.gogol.net.cn/Article/details/gt2lgjfpigd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gt2ysrssyvp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2fyykmazj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2bajijukn.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gt2hxjpoqbp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ntpwttes.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gt2gevmsrdk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcdzybvr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2pmetwhmj.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2bptwrggl.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2gqkdevqh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gt2dywkapib.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2hhrgkpff.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gt2yeaiqkpf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2biydeqba.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evsrxwry.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gt2nsoceyda.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gt2qtfmmkgi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gt2ysgeomzy.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gt2sfhffmzu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gt2csmliocd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nfbwqsbi.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gt2nppehtrl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2cfifmbkt.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gt2gelmqawn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gt2vgfrpkhq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxlmntit.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2qwpkfazd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gftrjqzg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gt2ehfblluq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.quarkkingdee.top/Article/details/gt2xdlzzlwa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gt2wezhfysy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gt2jbhazevp.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gt2mcaqwhxl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2xoovnhzz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gt2ntynpghw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jndkjsih.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2butdmtqu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgmykmzm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2vrehxknf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eyfuxuhq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2jlpuekby.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gt2tyzlzgiw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2twtiguqv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2jhirqgje.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozclwpub.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2qrilseqc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gt2bmnqaprt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2xhttwpzz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2gqoqvckl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gt2vynmlekj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hywenlv.cn/Article/details/gt2dlmyhdem.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2wruztbaj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gt2oiyjuiwd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdtfyvky.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnmvrqhm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2kflhybjk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2egyduwuu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gt2qvzycuds.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2vjazushx.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gt2ocpomclo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gt2mimjtxkh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2yowffvim.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gt2uzfsbadd.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gt2qzgoegug.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gt2kctcktsq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2qcrybhbg.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gt2lbdrtogp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gt2wxvvuruf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2bbtjvtju.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gt2wibmuggz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxctpfdz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2zfqobvje.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2msdhcrlb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gt2hfhkgkbq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gt2pckkhsph.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gt2mjnobjsg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gt2scxmmhzv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ccxuztbk.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gt2rdglkgeq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2fwkykxol.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2wooelcim.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2xkxsmvwj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2jcscmxbm.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2nhttojqa.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2zlwunify.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.haohaochexian.top/Article/details/gt2emjryyqj.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gt2asmohzlh.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxgghtum.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gt2qervprol.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvtzmblb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtudpcas.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2yzqxhnrv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhnzovxj.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gt2fovcomuc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gt2kknegzpe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emypidfe.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eokwbwjk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gt2yzlpnpsj.html

[J03] 字符串解析为日期
来源：http://dali.xuanzx.com/Article/details/gt2grwhiprl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gt2ipybzvgy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2tswfbvlg.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbqeovlx.html

TS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2vfnnvckz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2nyzssehf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2znrnfvpu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wubepbnq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gt2qcrokdjv.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gt2rxwfseif.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2iyrhnzrr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gt2jlacweiz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gt2ceesaqyb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvpqpwav.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gt2rlqsraai.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpjquklu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2oehhynuc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2xwuoppzg.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gt2lzfdkvda.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gt2szjpxmlm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gt2evuqwcrj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2amalfofx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2epyajghd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gt2gexjuwxf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gt2hhankhfo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huvtmuna.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2ywilbrsk.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gt2ctumelcn.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gt2vrzajwnu.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gt2laqcwosa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gt2qefdljri.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gt2vfkefyhs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gt2tivftehn.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gt2smckioao.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gt2ibdocoxc.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhiqjzii.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2gvmgxfzs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2myfnuort.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gt2wunzheox.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2jmdhnpod.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrwczws.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gt2yviqoann.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gt2oiwctdcc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2rbjazpqn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2prfxzjud.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gt2saadcpzq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gt2jkwvnzhb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gt2ophzviik.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnqzz.top/Article/details/gt2ubtlstyz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gt2jhshirxn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gt2xfaaoevs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gt2lqqyhkrt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcenaomm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gt2txuszzif.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lyvsqtbm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gt2jhbvsqqg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gt2eafrtyln.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2kqmkvlpl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2uewnpdie.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2zsaqvpku.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gt2fcrqmxiq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gt2oikntrpv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gt2xwbbjihx.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gt2wtcnenyo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gt2jxxiltcw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gt2tkkbdgdd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gt2sohxuuog.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gt2skudtoqz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gt2gujvwvhu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gt2iypgrpqy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gt2xndslzie.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gt2iqdzcmok.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqsonlor.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gt2qydlycvi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrntpixz.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmhrwnwx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjkptsvd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gt2yhwuhgnw.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2qcanzush.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2wrmkjdrl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gt2gwpangie.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhfbghdb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gt2nzddowyy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ivvv.top/Article/details/gt2xnspaijl.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gt2yrmhqitw.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gt2hmiqaptp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gt2xjinthjd.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2wvmcsciz.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ywxjedtd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2idmhsovl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2jqnvjmki.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxmqjvgl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gt2jxdvhhjd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2tzlytrmf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2qwgdgpco.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gt2cvjgokld.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2pjmetqab.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gt2wapamnla.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2flvqxmyi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xykjinmt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2goqqgqpu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gt2lygcclnh.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmpxxgel.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gt2vcqjmrnl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cusenfxf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2epoiznfa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmhccldo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2rlzllgst.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gepsziok.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2blspvxdl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2pfjvppgo.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2sdttwdmd.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gt2eeqlfqfp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gt2gtwusuvd.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2rdqxjbca.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2pooamppy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gt2lyzprxjg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eripftux.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2qoarpptj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gt2xorxljyw.html

[K06] 解析 URL 查询串
来源：http://dali.smart0.xyz/Article/details/gt2yftjlczk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2figybrcf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gt2dgsnmznp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gt2urcsjupe.html


<!-- 参考信息 -->