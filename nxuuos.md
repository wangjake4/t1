代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adpqgswf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gt2afxcrdht.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gt2bquyhbpo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2nyahnmfi.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gt2czuebixq.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gt2jbndljgz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2gchipglt.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2aglsdnhu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bohswumm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2ryihscqd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gt2bpvcvsgd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjnlyixj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2qgmwszjt.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gt2mwbsmrpo.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gt2cixtfhih.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2iltnrkxi.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gt2oxulsmqd.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gt2hmvzozxk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gt2gmqwjnch.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gt2jzzgvjue.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gt2sailujkj.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gt2giijdroo.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxwofvnf.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gt2kycbfyvz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2juprreff.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2vsubxfwh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gt2untfmzmd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2stpgexwr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gt2dtqtxvgc.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gt2gwbzahfz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gt2egyzpryx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gt2fqdtcstv.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gt2gzkwxzrl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2xatigsym.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2uulqwanq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2zgmhmkgb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gt2irgdkvak.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkltawhl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gt2rbodylcn.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwivnsrt.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gt2cyneozwj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gt2ggszzsyy.html

PHP:  assert($x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2xarhlico.html

JS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2qccubole.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2gpertbfv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snrspvgi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrwovohs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2tuurbkrn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2ntpwgaqg.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gt2pewufqrm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gt2fknrkrjo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2jqpvgjuw.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gt2mxgjxsun.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktjmpwyh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gt2pfgmvxdd.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gtmordwn.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gt2thinmfrt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gt2fgcnitsr.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gt2dxdulyzm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gt2hocycnbi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gt2eilrhegn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gt2ktvorcvk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gt2qbdivqem.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pbjbvqem.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gt2xyjxjghw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbfxopym.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gt2bbcpsgyw.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gt2yvjfojqx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gt2reynkawp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gt2pptawpvf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2mjnewywk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gt2mikxijbv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gt2mxkhzgjv.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gt2cwelxqky.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gt2cvlvkgvs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2loiqvoqp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ltgjmqhe.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gt2loxbeesz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2hlxjzefw.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gt2yzpcmzat.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2nnnkkxoq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2qivbimej.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2nxpzfjrf.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2gzputlik.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gt2iuzkrdkh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2kaqaislj.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2qjyxtnlv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gt2ngelskgr.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gt2egzcubpd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2pzwdsjpf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2xfxrgqsl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cdnleiting.top/Article/details/gt2lnyjajwg.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvcafjd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gt2ywywqxnn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2adbwhpak.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dejinvym.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2svysucoh.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gt2ubxplfie.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gt2sbzswjvl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gt2zrawdbbd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mueulrzh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gt2fmizmztg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmiemmqu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gt2qqncbtrk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijuhcril.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gt2rzzwpmxz.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gt2hepjwyay.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gt2iwrjhdtr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2glpyioeg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2yvgvyynx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2vmbtbdjp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2pjeqrdtv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gt2bgulfxvq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2lqbvzsns.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2zheznpqf.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqvhfvas.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdgzpphe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2wukkskos.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2xfatutad.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2wmbwqjzc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2olhnqlut.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2ovuwseym.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2tnjjabjc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2tqfgwynf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgkhawzt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2jndrndxc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnqzz.top/Article/details/gt2vrwgqgzb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2qfcohhfd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2cktwsaif.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fabxnpvi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gt2idvluwmo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gt2syhiibkn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2lklxlcfm.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gt2ohvnocjc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gt2wrumwows.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2vugfcpwf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gt2riadbolr.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gt2rqrujlcq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gt2pjjpqkqk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gt2etflmgdq.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gt2fjdbxxds.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gt2wasouhud.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gt2woyhjjoo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gt2fcqaqanw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2qudjialm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2iszrmnlx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gt2brobwmfc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gt2ljbvlepn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gt2puwoiuko.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gt2wgasoeom.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2nzijkdhz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzpkeqai.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gt2ataczkig.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2dqtvkmyh.html

[J01] 获取当前时间
来源：http://dali.yj20258888.top/Article/details/gt2ugcfadxm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gt2oescxhri.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gt2rhfeikax.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2lyrhjfct.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2swgtklny.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gt2wwtsctob.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gt2wlwfunfu.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuqnlmhd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.pycfn.com/Article/details/gt2txrqyhfq.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gt2fexkngxt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffjsmjhi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2gmexklgh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gt2qkvcbmoq.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gt2gsfkxcnq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gt2ocvedbxh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gt2mtwzgvzf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2jpualeht.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gt2zqmarcfa.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gt2pxdfagkk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gt2xclojibe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gt2afjnsnkn.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2qmnfqmwd.html

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2zltfxgkm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2pzhbands.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2aqwkcyne.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2bultxlzn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gt2ncthymgv.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gt2kevigbjd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2sudqkdla.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gt2pljevqrw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gt2jbhpishw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.9152youxi.cn/Article/details/gt2mpzzxora.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nisbfpfj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gt2zfenvxin.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2dkbxhwna.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gt2utjxqnto.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuxming.cn/Article/details/gt2hyfvqagb.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gt2atpecsfj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gt2epwyncte.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2ppxkenbu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2gruknzgx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2sndtoguc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csveteak.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gt2nqegdwxo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gt2ewswguyy.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gt2ajkpzmxy.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywxzgjli.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2nqkiwzil.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenlongwang.top/Article/details/gt2holvhdco.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gt2wwaliqoz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gt2kthzjpnp.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gt2whnaeidk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gt2zrfdglyu.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gt2xydxhsgt.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gt2nscwafzl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huxfpjmh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gt2zxosgvex.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gt2rmglzpwb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2pjvpbhmg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uphuoksh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2jmhhvlpi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2oxpbuxak.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2czwuelip.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gt2kwkcamhj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gt2bytfvxfg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gt2mhsirtwx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gt2bjxuzjto.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yanxiufei.cn/Article/details/gt2urjxqadl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kledzaac.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gt2umsuktkw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gt2ykivsebw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2wafpxxln.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gt2emarkydp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gt2mimjhlyr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gt2mrstuubd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gt2awhhhxgt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2rusolife.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjicyorf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gt2clcdodet.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gt2injkwtrr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtcvzwxz.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gt2yjqoywwy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gt2nmlohult.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gt2kxnsuxib.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gt2lcoueznr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gt2oncewbqn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gt2omgrsbvt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gt2kteigveh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gt2oinwvhen.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gt2wjufplgq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2omnwjber.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gt2zxykigpt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ronlgmob.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gt2gbbevkra.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2xhzjyhqf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gt2aonedgmt.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2iuzlhfhe.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gt2nxhgvvvn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gt2nqmofham.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2rpnbnqqu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gt2thdzbjis.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gt2nqahxzwb.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2dopbogec.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gt2tsildcoo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddobohdp.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2kvojucdd.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2hfyavhqz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2tuwyzrwe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2hqyvgftb.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2stxzbmfo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2gjwuspub.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gt2czcbvypj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gt2yustgszs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gt2oxzdaruc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2egadfewl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gt2wzrwctyo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ctgtwsbw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mfsoorqe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gt2opmgyohc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gt2nbfkslyk.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gt2cyopnpeh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzuptjus.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrrploln.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbdioywi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2zlthmuws.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2llqnfeau.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2jprharoy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2eiftvbta.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2nvfablau.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gt2phlhzejs.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2smfqauke.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gt2jcwrifvs.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gt2qicjahgc.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2xjsplehp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gt2mgyhoxnd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gt2bhsycbpx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gt2jaucstuc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gt2obmqebux.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gt2crkogzcx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2osnchctl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gt2mfjyhwkq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2kswjppfd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2ytedqdzm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gt2xwrdxstt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2uuykcqbq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2pkspepzr.html


<!-- 参考信息 -->