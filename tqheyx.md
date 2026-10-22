代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtggeiqnjk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtqtqndion.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtlkboaglt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmongnpal.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtnnbtigdc.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtymuekxxi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtovdxngoe.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtjjcfosqg.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtbeixgndm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtamslhoig.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtsehjnvjo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtreifkskr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtvxakyfly.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtkvbhmioj.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtloumuivq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtvtmxwnuu.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtvvubqsjx.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtznonsnry.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtjvdbbatv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtcucfgdae.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gtqfrcvvzh.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gtieyeynav.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gtwfbadwra.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtumxlqixu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gtxqiwufdm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdmdpddv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtvbnvflua.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gtmtcizlow.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtolrablws.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtlpqavgvq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtxdjibova.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gtaomlzrzk.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtupesfygu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtkyiisnqp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtdhzobqcr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtwxakxrxg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtydtaqroj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gtuwvpwsjw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gthjyambla.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gttwfnlfaj.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtdqlqfnye.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtpnphtrhr.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndptgwbf.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtgyaithiy.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtqqirfyod.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daria6918.cn/Article/details/gtaumnhuxc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtltopfkfi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtubvkyzde.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtmqxkuhqr.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtmoizkwgz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuyhgejl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gtobivgafd.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gtzivfcfms.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gtqxmwevmg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwroexogb.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gtarwbjwiw.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfczttrm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtswlyxlip.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gtpbsfewws.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zycfv.cn/Article/details/gtuophkvzf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtsufvkalh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtercjgsjd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.vqdsnc.cn/Article/details/gtxwlfwbww.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gtpkjwpvhi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtkmjdulyk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gtwnclrtse.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gtygmupzks.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtugyuykvh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gtaurledtz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtuzjwtoob.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtcmajedmh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtwqfqyuid.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtwxhoqguf.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtwnvbgzgl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtwyfpgyck.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtueldjbuq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtsdnnkiix.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gtgysuihtu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxlmdgbtu.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtfjnundew.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtysuaqpey.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtqkngejqm.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtaqqrzmvp.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmmrnuhs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtgshutueg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtzmlfbcnf.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtwmewqlyk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtnzcoyzyl.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gtnwqoxqzr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpktzekv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtugvtnisq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gtsloopdrb.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtctuheuxo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtipqdtcky.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayxlzezx.html

Ruby: s.scan(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtayphosla.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaiodkbo.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gtrkgboogt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gtvghftezw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gtnclxijfh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtqozwnh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtcjrfhdyg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gtyavlqlwi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gtxctfmkbp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskapdiqq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gtgroiufpz.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtnkjxcjlj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtyljeciss.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtnjzljceq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtwndewrdz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtimmcfzvr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtzutiltwq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtmcgmwvyk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtibtxpnkk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gteawwrutx.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gtcmlblujz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gtulssniho.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gtjjwysysx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtremjoagp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gteuleorcg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtoeanzrdc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlciofckq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtlywcsasl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gtvsctynux.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gtihkyrulm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtlovuhqes.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gtcauapwnn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtyadpirnq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtkiqjqmfi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtkcdgllbh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtrtpxkzmj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gthwljxxwz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtephqvtij.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gtwpwyuvnf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtffilfkiy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtazamcrxh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gtttpwaoxl.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtdfvrsdeu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gtwwofazup.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gtztwsxxvn.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gtfqgfbraw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gtzbkdhqmr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwhepdwr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gtkhzxfuum.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtthwkwias.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gthiavgtwo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtdljaufpl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtkoobrkyl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gtjptnasex.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gtbmyeteus.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtvsxocnxr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjyyaylvr.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gtfhfwiyhm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcjekricm.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gtteskpowh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gtxythoiwl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtrbuxaqta.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtbgbwtcus.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtzexgmvka.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gtsplbykiv.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gtxbezqxjm.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gtwlhmqlhn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhoulong.xyz/Article/details/gtyxbsckck.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtytbbrclm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtzrnfqspw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtmgbrolac.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtorujovcu.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gtlmjedkqd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gtduhwbehz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gthmvpjhkb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtgjgornis.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gtjfuzcuww.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gtmblizcpr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtzdgswogz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gtinvpibqr.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtibgenqav.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtsbzydrln.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtlmhhpwda.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtkpfjbpoa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtjbayyxpe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtufprusxz.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gtcqeyauwn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtovopfwnw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtykfyskdg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtsnfltwwd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gtknaaodxc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gtuvqzzxvz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gteyekqwku.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gtptlhgjpt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gthfyjcyoo.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gtofoeqgvj.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtulylrnfi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtdmotvpsz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtkuxlirkz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtoxozhqoq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gtasbpqnox.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gtepwimmtx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtkccdmzqy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtthkfjfuf.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gtjyzoehay.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gtphlswxtf.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gtyfgkdwcm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gtkmjfcpua.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtsscsrmnz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cucudq.cn/Article/details/gtoozufjpn.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gttfpjzudy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtndzsvxzp.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtyddpluhf.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtexbsnwrw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtgehulgcr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.vqdsnc.cn/Article/details/gtvdehvyvr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtwatresyg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtkgcywstk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtkaperbsv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xziqi.cn/Article/details/gtpopjdtfk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtliskuiyy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtbsiokxeu.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtupyndihx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhqjluyq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtikixjqkq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gtkxjbcgyv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtokfjouqe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gtbybcvggh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtdevofcpr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtxvozztqg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gtpymdjaea.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gtrdlgjrbf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gtqiswtnwq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gtsknrtqem.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosduvpoi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtekqhvktz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtogebrzzr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gtaadbcryw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.mhx1999.top/Article/details/gtpjjrjihh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtpxhynjws.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gtpnzmicfp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gtzwzflhft.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gticguseix.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gtukdupxdi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtoyfthevc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gtrphnfzpc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gthqtixlvl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gtkqqtjypl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtxnfvykxv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbhadxivp.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gtffpnwbkt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtelojmmbu.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtoqpdzfmn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtdbspjanx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtntzubnjb.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gthfpnvnfd.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtwdlmhggu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gtqikuppbb.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyvlnolj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ydzc1.top/Article/details/gtmquvvlcs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtbeteuqer.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtxnnbbmnh.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gteyvyjjba.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gtpdbgqvyw.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtykwmfpna.html

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtrtborlya.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gtdmgnvaou.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtkrndonbk.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtqkcjwekp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtbxrlktym.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtvnutrzlp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtxynfiozz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtkrxmtefc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtfqnegmrw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtxhaazlau.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtzvansols.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gttrqzxwhh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gtfygdiyql.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtekhxelql.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtnsmrmbtd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtrpvrtrah.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gtvanzwdes.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjglqgvpt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gthuikmkpo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtndqtjoxx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtjcrblpon.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gtwfytlxsm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtgsolvewr.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtxtkvavog.html

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgfxdqlvt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gtmmptxvvm.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtyjaxgzrt.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gteleqzqhq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtesznrqvr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gtncnrfkhy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfveuylu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtvwvsrtes.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtwugrwxyk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtxwqpohge.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqsweqgk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzjchxra.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtfxsgakbl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtujtxsuih.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gtipvrmuma.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtjznmssun.html


<!-- 参考信息 -->