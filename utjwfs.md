代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtkbxiuggh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtbiztauca.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtghtggzvd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtlhytacfi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtlbaqvwth.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gteuvpltdo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtgwvcchrm.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtkejppmih.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gtdodhimpr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtaujwqntx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtzehzdwuw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtqgpzrmzu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtwtepjhtd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gtigexzijt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gttakpohng.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtvnojdztd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtmnpmlrkg.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtncnvoaqn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtiilhokny.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtnhbapmiz.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gthpzpbwlw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtiykwugew.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gtpklvsars.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gtyuayasol.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtlxruvars.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gtfuveqyit.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtsvfbznvp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtslxrwnbj.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtnnzirvhl.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtmhnbbyol.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtceqmccgv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gtztwgynsc.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtiwvuufox.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gtmeyewxtx.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtklprolwh.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gtkhaxvvcg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtwyiubwnd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtdpakjxqm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtkxrpwubl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gtobraqnzo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gtisynhusu.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gtemyuurgo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gteuuwylbl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gtryemqnrn.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtgpabgczg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtdcspicdk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtwpfqkipf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtuqanlhks.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gtdjkwdegk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gtdrzbador.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtphnjefio.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtubapkkvz.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtwkimyegr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gtlsvlotku.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gthkfrckcb.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtjisrrxnd.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtgkvcdhhb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbwfpgqp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gttepkzafn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gtlvtanpci.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtvdupzqvn.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtgaefexeg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gtckpiekuq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtwzgshfss.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtyqjjfhnr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gtmtsjmtjw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtcmkgognx.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtfirpiftd.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gtzgdoczav.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gtljbftyko.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtwlwyvbxk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtnbnohkpr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gtjajjeqrl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtljkjzwqb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gteddbmaar.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtsjndmksg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtbthnlxed.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gtedmqdllr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gteyfkknzv.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrqmlpzp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gtiylyoppi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtgbvzfjjx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtzpchpgmn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeefvqwa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gtpfzkinif.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gtseswelzu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gtelawvtqj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtcbxwnsox.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcifmbeno.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gtupdstjpo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxcemdlxo.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gtihhissoz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtdiyydzgr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtqsftsrhx.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtbophqkzg.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtrzxqtrbu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtyiseeveo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtdptzxvze.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtncjmljnr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtlcrdvtgs.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gtaanviaaj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtgdztgyeq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gtcvucykmq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gtruljsqsg.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gtimxyctbs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gtqcahhiey.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtkumjdmyd.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtaidobmwu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtdtgqewoa.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gtnhasbkkd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gtzzwptnrg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtsrzgztzl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gtxokexdag.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gtjnairstd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gtkotzkxer.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtjxwzjrjn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtnozsxnrf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gtrzuymudr.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtpqazrvrl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gtscljwqca.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtxhzlsktl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtznjkswql.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtsrncduxc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtktxhrlhl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtctlozuyr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gtqqvovvmw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gthqudmumx.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbcrjvhm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjziookmv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gthfpxkgrp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gthaiapvrf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtiwcykcdl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriuobagz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbramkedj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtctajzvvz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gtdngbwver.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtgdbepfmg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtxkjdtliu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gthsmgbdze.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtiqsjiwlv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtifxkfgxp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtqdnmbtwa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtxpkzrklk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtaucijazw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtusrjnxsf.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtblfhcpjd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gtkoqpmula.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtmkepzifl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtmrdwyfjk.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gtirarpxfi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gtxteaozlt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtrmjicohi.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gtrcgypuij.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtlkldxfkd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtplomjtoz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpjbqdkz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtpmsdhote.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtwxqfrnie.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtnnuowjuj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtiqlgncjd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtudczgusm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gtdqcehyec.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtjphiwabr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtefgkmexy.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtdaqlirlx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtktywnota.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gtzasnrusd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtjahnmxmt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtfzkxamrk.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtzraheqrh.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtfdngohbt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gtxktjnthi.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsccoapxz.html

Ruby: Time.now
来源：http://dali.yongpay.top/Article/details/gtmoncqbrl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gttaptetdm.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtwcolewiv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtbtnzfzjv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtqwwgvygd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.haohaochexian.top/Article/details/gtjzgonvti.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtyomjeooh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymnpnlka.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gtcahfgcrx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtjeujvklq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtrovtcees.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gthfeoauqn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtwymdraid.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtbnaehwqn.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtcfnvpydo.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtvfpymqui.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtwvctuwml.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtordtedhz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtqmakjbof.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gtkkeaoyxh.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gtfxrvlkjc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gtmddnykpf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtzoddgbmq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtndroevxl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtyrsnbwbz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtzvlhmerm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gthrgywfnm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtzgrerdov.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtqeiiwvle.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gtmqddqroh.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtlhhawnjr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gtryxkjrxs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtksyvlfmp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtwgdaoqvc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtfdcqkzeb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gtrxtbkcjw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gtsvxgzecc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtrhyxafhm.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevdsrddd.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gtkheeszyk.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gtifqlmmfd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtnzjvcskw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hfpthk.cn/Article/details/gtnlxrbbtl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gttfchlvoj.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gtxfzfyoey.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gtguqgjjds.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gtueezptyu.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gtojrqisyy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtmpivagmm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gtpkxqjofa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtpabkqwxx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtkldlplvc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtbuamwgrk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtoohbwedu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gttqhngpux.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxishboj.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtzihrcrhm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gtopzbnosw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gteduxswfe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtcczmvjkq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gtgwjxfzen.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gtcjlguvis.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtgpnnwzzv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gtjarokzrt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gtwdluheml.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gtdznvjdrd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gtgbrkqdcv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtuqrifdqd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gttwflwkle.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtqemdqxyk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gtpiuzcecm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gtxnkcgypk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtoxsdhidi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gtpxqaznoo.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtiujqzwul.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gttknwprgu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtfsgmjhop.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtianusuyt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcxzcpmi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtjsohjlbb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtxzqkvuoi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtfnqblfhr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtmefxnmdw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtukzntzbk.html

K. JSON 与序列化
来源：http://dali.fengsongda.top/Article/details/gtghndadks.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgvryelfb.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtcnutstqq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtqiwrdyde.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtiluuskga.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtvwvirtac.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucuzzllf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtycolwtoj.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtaweeslfl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtymlapiwv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhmgwbol.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gtuiilemwx.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gtxinntncy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtftsqtlmk.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtdwvaotgh.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtagqbiewg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtievsphuf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtyntcpzws.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtbejmoxoa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gthhwkohcf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gtupzdqspp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtjxusjkdl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtycymlbtf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtlpmzkayr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtjiimulbv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gtjunkymnq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gteuovrpby.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gtuqlnebqm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtwjawqkfk.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gtdpokhxrc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gtwbppxgkh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gtzcczwvsr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtoyxsvcrm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtxpdxwjas.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gtpvxlpceh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtsbrpxwov.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gthipruutr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtmsxxvhpp.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gtkfhguobl.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gtwfdvrunl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxigzuqf.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtosqqfkfd.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtaxmdfvyk.html


<!-- 参考信息 -->