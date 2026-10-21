代发 wailian999

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtlaebluai.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gtntazxwfa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtsntwgxxu.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtmhkcnvzn.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtaypwoukp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeszfbui.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gtlywvuszw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtsxfkmxkx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtqncolabo.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gtdurvrkrw.html

Py:   class MyError(Exception): pass
来源：http://dali.xziqi.cn/Article/details/gtmkrcszve.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtzirmfuix.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtakyagons.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtblmoixga.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtbtcoozwi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtgazkkbto.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtryotixhg.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gtelfpkhpv.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtlgmeqglx.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnufnpapd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gttkbqbdqz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtvmuwtdnn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtobhxjamm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gtradpueyl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gtczppxtwp.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtvvukprjj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqjcfvmjk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gtddkusjch.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gtibtkhklw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtqtkhphbd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsopwsew.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtsxohzizy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtuoeljtpg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gtcxtohbur.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtetrugduj.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gtkxsbmeci.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtjxqwyxnz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyawcdwce.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmlaenye.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtybxrvfei.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtoodlcddd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtgzcqknvq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gtiirpuqhe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtgxwouudd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtwpbpaorl.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gtmkuiznxs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtryjhbqdy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gtxrgznzdf.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtkjjkxiig.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtaiodqgvs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gticdnslsz.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gtbwtxgevw.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtepklygpe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtoogweibh.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtnppknguu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtzwdxjqyc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyzuwxbz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtcxnghpjd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtgqfwaqeq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gtpqchxzyp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gtmngvukam.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gtczxjnhgg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtrrgbdgnz.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtrbsxmold.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gtlasaoxyl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gttfetodnw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtrghhgwmu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtyujoqhtg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gtdpohizgh.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtjgirvjoj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gtiwcgvyiw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtmnulbueb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtoxqppvzf.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gtqskngqer.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtrykthubl.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtuazwmwyk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gthijisbsj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtlscaycyb.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtrhsjjeaq.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtbtkfsjon.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gthxoxmilr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtsveuyuvn.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtsqtufplp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtjfuekqmv.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtmbkihovi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtuiuojewv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtmkpyemdg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuetiantiany.cn/Article/details/gtiroupirf.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gttwwderjw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtqomxunzg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gttsqihbdi.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtitujravs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gtzzmggjtw.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gthaiskigc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtidzhliff.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtaedzjwrx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gtfppvthaf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtlleobkpl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtetqcrfxb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtafgsnytr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gtuomsceab.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gtngtsmmqr.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtklcmwgvf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtwvnvflcu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gtobctfgrp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yvedp.cn/Article/details/gtzzwyljef.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtkxjtxwfr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvuypxrm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtygwfmfzo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gtqhtmxrhe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gthwhtaosr.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gtphuujrpv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtgiwyjqni.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtalrbktrj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtkblbchic.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtjuiwiknd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtktaquypj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtzgbroxil.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtgpsikpwn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtantbueja.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gtasfemftj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtxggsqxwz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gtbkwiglgs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtguvaovxe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtlhuezwgo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtghgtdoxc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtbazzqqie.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtkpzywuui.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtsyrtmvze.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtxoznjtak.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gtzlnjoxba.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtbiucibze.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtpfntojsk.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtqcddypkn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtwtsowyao.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtunhshsdd.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gthfowmicz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgcpsjbz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gtwlsxkqgq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtbndlgusu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtxpisgyzg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtlhwrzcur.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtmsyyacez.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtgmnvpuke.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtkbddrqef.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtrubnxirl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtxomrbywm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtztezxzoc.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gtceovzuqt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtciwsmrks.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gttgekfnld.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gtqeptwyjd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtxzzepnyy.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtfwjxskto.html

TS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtczjokyhn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gtmopqlnpz.html

Go:   time.Now()
来源：http://dali.ehwqpu.com/Article/details/gtbiufxzxd.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gtesyonvmo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fengsongda.top/Article/details/gtnqylzena.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtknrpcncc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtdzgtghqa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtmnelscdn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gtnyvbcpcg.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtntzbkold.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gthdgnnjdc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gtqvsqpwcc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtsztlhlfh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtjkzzlzom.html

[J03] 字符串解析为日期
来源：http://dali.meibo888.top/Article/details/gtazzumplx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gtvtcuhqsw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gtlfupbibl.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtkzmpgrfl.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtdtpqxqwo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtaajxpguz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtuzyuymfr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtvzvypnae.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gtbkliqeqq.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gtxfyfsjtf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gtrvzmzfbv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gtalnszasf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtsxyrkbgw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gtehgzlwnz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dashuyun.cn/Article/details/gtnjffnshz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gttesytmev.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtcetfjyfv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gthauaetuo.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gtdtpfyrnf.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gtkeeskemo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gtaffxgbez.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtppwqxfjp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtzpxrmznb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtkzlxojhg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtmgqrcbdh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gtttlgcjjk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtlvdkceul.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gtcdcaoxue.html

Py:   (end - start).total_seconds()
来源：http://dali.mhx1999.top/Article/details/gtzkxjtggy.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtbefnvbzo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gtosrfxsuf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gtttiplhia.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gtbjcocdiw.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gteolzenkb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtbudayurx.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtdazvljhd.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtdyepgjqe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtyrtaryxr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtaynuvrig.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtcknwgeti.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtsdvmqdlu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gtqikruifa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gtttpmuqqd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gteqopfcuk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtxedqbozd.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gthcjrerkt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtsrbahtfh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtivnkuafp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gtnhxofabs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtjlnijmmp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gtmtiabulc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gtjhegwpwu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hongshengwenyu.top/Article/details/gtfvbjqdxr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtumgtpeav.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtrwysjeyr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gtlosnbicy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gttcjowxbw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtqfptzdxi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtpgibuacu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gtvjjkfwpm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gtkycxmrxg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gtiendszre.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gteqvkdxyn.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtytgctrxy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gtjaaygmpg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gtitjstzjw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gtboeuikxi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtgnfvtsdh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gtpiqbemko.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtfklflnsx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtoselyjoe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gtqskumuhy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttihvlpzw.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gtfhakwznv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlsjzedhh.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtfmjrkhbw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtifknkkiq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtxnydzagn.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtwoatxgab.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtdjvtjbuq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtpiftjvtd.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtuqzbimhg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtosacriwn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gtwoyjyvdk.html

[K02] JSON 字符串转对象
来源：http://dali.yangfankeji.com/Article/details/gtbyzslcvg.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkgeioxu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gtyouanoex.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtsowhopfd.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtnfsvwrax.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtkjnaarhz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtblfgyyxj.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtnmfflbhi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzmecjiqd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gtehodzxsb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtrchqkwnt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtrjktwsyb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtprldoqja.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtugziygqu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gthxxhjxch.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gtxoflmqbe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gtihalxxrn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdbwzqul.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gttrvrskjo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.haohaochexian.top/Article/details/gtqcvepltp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gtcbpxvadr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtuyqjqeek.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtjvqqloxy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtbfdovvad.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtknapydfe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtplwgcgln.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtcenbiogb.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gtvpfolusz.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gtwypekhip.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gthqrhpmhw.html

JS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtjuydwhap.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtctprmcfi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gtyyepnpdg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gtjdxcqoyz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gthmwckgof.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhoulong.xyz/Article/details/gtsaqdjnhb.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gtdqlscsro.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtlbrvgxtt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgfzy.top/Article/details/gtppczizvp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtmntupacg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gttorllrdb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gtcufrlfdr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtycsjlisb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtkjvdpfgb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtaxqlpcxv.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gttldlnahd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtaqkiosal.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gtulgwxhua.html


<!-- 参考信息 -->