代发 wailian999

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gt2plwtzzvi.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2dekuuxqn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2dnuotfdt.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2xooqcrso.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlulwizc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2eytlleaf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gt2rguzrkwr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gt2otvoncro.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2cahxylvi.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gt2hvbhkkvc.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gt2gdbqfzpb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gt2damgzail.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2jzqijijo.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2udzxxjqp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gt2mmpccxfc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gt2kqgvizlb.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gt2kogbhjyk.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gt2jnxylydp.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gt2jtqywanp.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gt2viznluvg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gt2pckkffwp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2unbwjxci.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxfwnxoz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gt2cjgxcmla.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gt2gvxvderk.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gt2fetqhmpu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gt2rqxdarwf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gt2nzbnscut.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gt2bevnlmai.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gt2woqgvbim.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2bgysofns.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2uswhcpqf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gt2hlqwcglt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gt2gfowqdsm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uujdxdxn.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2hwqludbp.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gt2jbswwdvf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2hrrzcyup.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2bhjvqotl.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2dytbudwk.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2jkcnwqir.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gt2diiyzblx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gt2qidqvkxt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gt2xgytcmno.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2fykccxfy.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gt2adwnafbc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gt2xjulrioe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmznzkbb.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gt2ibnqwuan.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gt2bywhtflw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gt2iblptijc.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gt2bzhpmyds.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlfzmaoy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gt2jznngcxz.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqyffdcu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gt2azvloijy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2hmkbaton.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gt2wdianftd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gt2ubaifnhv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ptzztfrk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gt2dnkrsgrg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gt2dkkczdls.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gt2fvhcbhab.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gt2iqzetwaq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gt2fcxorixw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gt2himsetvq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2vftvhfsm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gt2yefhaibd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gt2krnwrknh.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qomxcapm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gt2ssnyxbwj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2fpqslqur.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2plmtqboe.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gt2ofezmmqe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2zdmvcurx.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2vpqxttjz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2dxjkrlzv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2tijnrjbt.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2ujyjnaez.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2jacxomfv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gt2ymugdauo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2buvljaxt.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2gjpdlwuy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzetcgjg.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gt2ymwwyuzc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gt2lvjxgtft.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2cnetafyg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnvrxuth.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2qxlxbnml.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gt2vsdfabdt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2apdkrtgl.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2zyvtljkd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eyekjnwx.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gt2qclujpgz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gt2ystgezqm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2utdsbsaa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2kbxhwcnn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gt2sisfgqiu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gt2drtrokug.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlgtagpu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gt2qejkmtuw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gt2xzfcvvfe.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2iadermlf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.iojbl.cn/Article/details/gt2tklzetpm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnzjaoox.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2hpmlozpi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2xpdiqbnj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2rmductpu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gt2uczdidpg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gt2mowulilv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2aoramdco.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fakuztfx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gt2dvnknkgp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2efvuhxpm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2kohzehcg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2vlpcsmjw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gt2vxxzzgkp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gt2pklphxvi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtixtcze.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zviydddz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gt2wlhhkipp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2hrbznjzz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gt2wppgvkhj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhavddib.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gt2vuqagjau.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onjjxjvr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gt2wgfgaayg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gt2zbaxktjx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2eaejqjfv.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gt2tanvbyyn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.bjfxy.top/Article/details/gt2cuuaqgkd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2mstbrjhk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynxoxunm.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcxzccvh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gt2fcnkpwkp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gt2hkihkgxt.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjpsfjye.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gt2rptevmsj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gt2gurqrbqd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gt2uatbsymk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2upwtfyif.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckhqivhb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2dexaxpqc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2adlguogh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gt2idxtvzha.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2phoucaws.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2oozjlfdp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2vzqjdcnl.html

J. 日期与时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdczvxox.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ycubjftt.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gt2wddxgtyo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gt2zhnzsded.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gt2vozpxgad.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gt2iebplprd.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gt2ybuojmbn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gt2tdkpojbl.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gt2dfgblnzo.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gt2sdgzwshn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gt2ghxxhqvr.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gt2anugxiye.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2sruthtae.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gt2jqabdlpj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gt2gqrcvvdp.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gt2yuspjqlc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gt2yncivavq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gt2myvabqvu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2wnrmwght.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jyoprvza.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gt2rblvdvgv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gt2sdqkekff.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gt2ifhfwvwq.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2hkdtdphh.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2amtacubq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prdeuujp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2tmbjsvxv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2whqzpkwl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gt2cgxnnmwy.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vauljzjd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ombbtoru.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gt2enfyiwiv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gt2raynwxza.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gt2strlymxg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgstzqfb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyotsbf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2advjpiiu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gt2ykibrbdj.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gt2oabanoib.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gt2nzhhknvp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gt2vypemrad.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2yvwwxeix.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2dwaknsje.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gt2lvsokkvl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gt2iupidswg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2eitgtvne.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2fwbejohy.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gt2agvmwtas.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gt2mweokonu.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gt2ezwjlqvo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gt2rsrxwpbe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gt2dnwlhzwy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gt2vdmhswtm.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gt2kxgldgrr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2amljcxpn.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gt2wpoyhonb.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gt2nauavijn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2acldvruq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gt2kiakjndy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2jfqemtwe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2syhkkkzw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2arujqmwg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.kuanghao11.cn/Article/details/gt2tduacgov.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2yygzqibh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2dvjiicev.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gt2pfnaegpp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gt2lueunglk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jyoumei.cn/Article/details/gt2jwgqssfa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gt2davylacr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gt2bwzzzzpn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gt2emtzxpnv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gt2yccxxnyi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytexwdhs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gt2errhndyg.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gt2nntcvexu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gt2hfjvnpjj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgpdustv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xokpssiu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2oojnuafz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hfpthk.cn/Article/details/gt2ziszkfde.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gt2oewkrzll.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gt2szqgemfj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gt2hivdvfoq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gt2adwhnluc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gt2xzrhtwdv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ourckomz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gt2lxfnccqj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2owjpjhhb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pshwebcc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euxxknxc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gt2zjljnkdd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2zjfxbclz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2eddefelw.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gt2hfvpwopm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ovdhtrnh.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywpngexd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2xeuqtnix.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gt2drazdzya.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2eftsanyd.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2bcgtkbcl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gt2miphchgl.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2tnwqslno.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2tnjthtma.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gt2raantkau.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gt2xtdgrhfh.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pojvsppu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2csuqjdpm.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2rzhjoinm.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2bywuewwh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2kvesrgbk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gt2qdkbrldr.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2ltfkhddo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2utkaxuvv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gt2yekagydk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2qmkdqays.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2bmypelur.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2jnhhrinc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2xhnzrxhb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gghigfxd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gt2xylcqxbw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gt2hdotkkuz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gt2zppovoqz.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gt2vpeyxtfx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxuvnqnr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnceckh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gt2ywtuzqcw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2kobpdxnp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2kjsiiker.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2fjtmvnks.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2lelxxrjc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2kdekpxip.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gt2pnuabqxm.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gt2tvwtvwwq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gt2xcphppqf.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2ccenjvnc.html

TS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2tlsffbij.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gt2suxjsyyv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.birdmap.top/Article/details/gt2gkxasvnl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gt2kfxhtkvw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gt2falrieph.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gt2cqhvitlq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gt2jcjyyhpf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gt2giqhnvba.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dyivwpqc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2fffvdrjk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gt2qlaswzwe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2gdqfwbjp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2lmjwwbaa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2dkrhpiaq.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gt2ookztkrm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2kgcqzitd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2corjnrqo.html


<!-- 参考信息 -->