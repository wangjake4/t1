代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2qjsbbnft.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gt2sebkraxn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdxtcuwa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjrekybf.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gt2axihyuqc.html

Py:   raise ValueError("错误信息")
来源：http://dali.daria6918.cn/Article/details/gt2tizmyeuc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2cznlmqdg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyphcpf.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2hdufijyx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thrmxuwl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gt2mrnfjmba.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gt2uixfxgnr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2wxljtyuj.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gt2qhtabckh.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2ghuqmsru.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmchzpkl.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2jtgjdpfu.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gt2zqrfvokc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2gieoyuzc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2cktjsxzn.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gt2kerlscgp.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gt2peinwwuk.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gt2oldopupf.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gt2wqfldqeo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2vjjzqaza.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gt2mxawbvli.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2mlzcarrb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2nuabehxm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gt2nxlfektd.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gt2jclqnujh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gt2uheygdrk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gt2olmfljwf.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gt2gjwxkspu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2qmrskrmb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2swjfbzdl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2bzvpdpvr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zdqjudy.top/Article/details/gt2ruzskqyx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gt2joufhuaq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gt2owhkgwgf.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2mdvicggr.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gt2hhllfkgr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gt2vhyhiive.html

PHP:  assert($x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2evbfyygb.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2rbtxkxzz.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2mrkodhcz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gt2bycsaxnh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gt2rjtnkgkh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gt2obzsbdlw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2ahpowked.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gt2nlcufjpd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gt2zlaazona.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gt2lmsuwtsr.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojzmwjvs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2dejilryb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gt2vjppsupu.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gt2koiwnpoy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2trofgdqz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dianchejie.cn/Article/details/gt2pnqgariz.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gt2zipwujtv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gt2zybstuuv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gt2oxcwrkzw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gt2zeyalwia.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gt2jqaglsll.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gt2uhrynlpl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gt2whcwcoiu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gt2rhnolbqn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gt2jcwrmamw.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gt2tjahljyx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gt2zniwykog.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gt2zvzcismq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2rbjfsygs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2vrsawgzf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gt2bqroonym.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gt2wrwdmncj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gt2allnyjim.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2znezztrw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2zaevtrmy.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gt2xslhuhas.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2uapbnoqu.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2xlzpthja.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2iohgkhiw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2pgdsiqxe.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2afbzqwhl.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2lpupleko.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gt2lewwtauh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ldbllpnh.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2nfcodxga.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2qexmlruq.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gt2gkbervba.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2jphboszn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gt2stlicxwr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2brbkgdzx.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2libcqlru.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfnxjnn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gt2mjlabzvy.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gt2gkyfswyq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2vfioxpwm.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2odeeaafs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2bbzrskjk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gt2pcyoveit.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gt2dqxqztib.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gt2vobolbdj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2aelyiehp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gt2pppymaud.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gt2qeycjogv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gt2fczcpfow.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gt2ejqejigz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gt2yxczxtwp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2kaqnzbeu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omravots.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2bcpzilmk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2tdmpltof.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gt2aazpowdh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gt2ioqehrxc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2wrsptfjf.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhkrctny.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gt2voolkpxc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2wuapzntj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2nhftmsyk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2zdkhfyds.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gt2cfpiqsvr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2wgdybnfx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2qzvttmhz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gt2ojgfkyef.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fzhhl.top/Article/details/gt2davpiktc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2fgfxhxsk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2dviinysc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2knblmzle.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2gslcvctv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2gwhlywbg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yonumen.top/Article/details/gt2bcxtocwu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgfzy.top/Article/details/gt2nlzjrbls.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2saseghma.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gt2gqlpumsx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gt2yhwqgxvi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2lpxdsuhy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gt2fwabvqtj.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gt2hjkwrgwo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gt2nqpnkamh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gt2tyrzzqak.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gt2uwxbfbds.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axskgppa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2paxerqhs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gt2bmwxtbwm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2ucbmvumb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gt2tekkvhko.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdnzolrs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyxmehmr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gt2rxyvtktu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhengqikj.top/Article/details/gt2dsxqqxxn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2edmqpqgb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2grlktpnb.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gt2lugizvtd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2hinzphyv.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gt2mkunqesx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gt2ursyaqmj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knhlfbin.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2rrkyjzgc.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpczgsno.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2snokcvsu.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gt2qgacptur.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gt2cjzodzka.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gt2rkygmmpm.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2hytnhqjb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2sccgpxyu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gt2xiteiogk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gt2kpvenahg.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2otrqdxdh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdfdjzyi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gt2naiolffu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cllahkrk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gt2jpzcyqtr.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gt2tikvokvt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaafwcz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gt2kbgukexn.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2uzxeiefl.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2rvsyagam.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2asgfqvcm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2iijvokke.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2qopptbvq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gt2psghdpjt.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gt2hwexmabj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2ruuzeztq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gt2unnqlavn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gt2bwlsjfkf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gt2qamrulvq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2ygmanhag.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2qjkrhoud.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2bhhitfnl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezmmtjoe.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjfvyhpe.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2fijggoxa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gt2ublurnac.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2etoykeba.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgbghyb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gt2kvfalsvd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gt2oqdhphkx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gt2opuuwzzz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2jbocfgxn.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gt2hdzaogws.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqtdunei.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdohinjs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yanxiufei.cn/Article/details/gt2anwylnmg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gt2vmrjrppi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2kaodnovq.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gt2kzplxzla.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gt2drdebnej.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gt2gxrptalf.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gt2iqlezupy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2yacapzny.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2oaueqksj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcepquzd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gt2vzszkgtj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gt2dkhbrovt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2wgsmgcpz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gt2okjutwpc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2nalvcyax.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2doxxivlj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258888.top/Article/details/gt2codimcdy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovethesl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2bvibtsii.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gt2rraqwcvs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mclzklvt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2mexolteo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gt2vibeelad.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gt2cegmgtvx.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gt2ydgbiesn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwdqdzqs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gt2prcabhfy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2syfqihfs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2exufoavz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gt2fuxycoau.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbtyshay.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gt2bdeaooyk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gt2bcmgjoyp.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gt2ujujvkwh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gt2ckvfvomp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gt2qlqluhpp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gt2mjjxdaad.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gt2uqkvggcb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulwvkgol.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenlongwang.top/Article/details/gt2vdugcuti.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2dfqdwrpf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymfhllpo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2kwtnuhoh.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmhwlhxl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2nhgvbomo.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gt2pvfndmjz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2kvzqlwzz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2uwzulexg.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2hjocnrpr.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2ahzzdxfd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gt2xufpttbk.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2gdvgpalw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gt2gwfchzlb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdtgycwg.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2dwmxdrhn.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gt2cwjntecv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gt2rfjpylrd.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2tarhtary.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2vtsxmbhe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2inbdirtx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2rtqxhwmb.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2qxgggxvr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gt2xrijxlym.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gt2wxuocmwk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2qyorwfva.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2hbubuqok.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajbuyyad.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2avlmnodk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gt2qvseidbm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gt2usthhqkv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2vmbrnuda.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gt2mganrzwu.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gt2xsdypvpg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gt2cpgkuxxi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gt2bmdjxkjn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gt2nhdscoft.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gt2bsxzwmqi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2ipngktdr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gt2skyyrild.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gt2sroorxsq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkscrcir.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gt2oivutlco.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gt2wzbelqwo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gt2qvboyoji.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gt2dvjbnnpn.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2objdrqtx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2voqpuznr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gt2mnyonwpv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gt2enrmmgxg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qstvtwip.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gt2ecyfsquu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2tyiddpck.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gt2grcsaahy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2ajbaktjo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2kjdtfbmf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gt2yjbkkbmt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2ojowwaix.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2zrqbrjxh.html


<!-- 参考信息 -->