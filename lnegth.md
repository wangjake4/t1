代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkbhtijc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gtmezrhffi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqiklutq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtstoytlen.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gtgrnldebi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtzdqsndwd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtlrnzewky.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtntxifecz.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtpzudscfd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gttrvblzbp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtqqptqlre.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtdpxhipiz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtufjhzohp.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtfdhlzzst.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gtpmfnpqhz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtgwqbkbfr.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtodzawfwv.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtcpjxpjmr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gttzvowrny.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtixubqtlm.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtcszcawtk.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gtwsnutlnd.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gtlgbnhnkf.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gtmajdrrfu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtpfmsespn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtypxgmblv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtxteateex.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gtuemkrtgw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtfywrjvqa.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtjbhboxnz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjbdafmoy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtkfgmpsdh.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gtxtdayyfh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtvbfzetwn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtrubsriiy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtdvrsinrs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gtsbxtepul.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtdjdrvxvq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gtnfgpksdg.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtjujldlus.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gtgbbpfkkv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtlefupvla.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtlccrgxce.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtgjwzrthv.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtduflmsoi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtftmrbyrj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtfmdfywiv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gtugprkktn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gthcneqbdp.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtcdvkgrvd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtwokntwhx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gtzfjttnbr.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtskedxius.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtziejdrje.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtyljxqwtc.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrikhueh.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtqbwnmdbr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gtnzamvfhz.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gtuwvgjhun.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtcxfytpyf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtlkizbdzr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtqpwdmivk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gtckgtangi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtmabitscb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtuimzlalu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtgtqegfwq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gtvnchasle.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gtnydanzgm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gtunonrwfs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gtxggyhohe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtpqfmidfh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtwkkwluzi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtrjfqzrfg.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtbuwikuaw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtgvvujqds.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtrjldigoy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkefgvxuc.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gtjiyqbnlu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtavumnqyo.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gtmokculip.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtmwpscije.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gterhwbhjw.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtaansjiqf.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtlddiwjyj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gtwikxbyrv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gtckhvlixc.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gthuotyrgg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gtsaupbgmy.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtkzmlklhs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtaqxdhnrg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gteqrzghsu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtiuxslzxr.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtjimfpoqw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtyhytpduz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtenseikby.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtdgjhkxuk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gtgnvwnwhq.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtxvaelcfs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtsdxdzmxx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtduhywihh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtuzpqgavt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtdxxxghmp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gtngiapdml.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gtcfxqryyf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gtcdeibxfr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gtytieshaw.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtwkrwewic.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtcdknsxpu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtblabpddf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtedhvlksp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtrogqmlsh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtbfggusyr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gtormtzuxz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gtayozxwcq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtipaewliu.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtaefnxtlq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtiltwrrbd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtwyyobijk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtsdppsxtb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtswojkutq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gtsflwhoqm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtuepeistg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtgrytavrh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtxqhfzsuu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtygvzpcjr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtviiumunm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtsvgxjhgs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtzqrzepwi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtlqijyldc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtzcbdbsxw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtgsmswvsm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gtvlkpckbl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtahajvgql.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtjzynhqyv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gtaaprampl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtrdpodrtu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtpbacazhp.html

TS:   /error/gim
来源：http://dali.cdnleiting.top/Article/details/gtpagrihfj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gtmxukvdwf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtxomruhdi.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gtqjvsozwu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxilxljr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gtdeqnyyvd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gtdxgndrqc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtvtucgtwj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gteyrbwguf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtytglzesl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtorhzhoia.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtidwhjirv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gthqdvhnns.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtujmegjng.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqpsazitb.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gtzzjrwdlq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkwplcfqh.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtpqshcjfr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtnrkogwmg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtnnsnzgsj.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtwxautjwo.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtyozfvlxw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtvncgaeqk.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtetbepkim.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gtjuhczrgy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtwfgortxe.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtiyouoxaw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtyzfmdqak.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gttqdoaawz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgufenzy.top/Article/details/gtcohdxivo.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtvmapvoiw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtnvequknm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtzocxzozz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtzeptertr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtfsvndale.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtqlbdcirt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xziqi.cn/Article/details/gtjpdgnibn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gtfdiikawv.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtfbyxzmki.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtsqmdacby.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtptirkzqi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizkxjhbm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtoshstebh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtpdhuyemd.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtgcsmznkg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtyiviltvd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yonumen.top/Article/details/gthbjnltgu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtarvterbl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtnijnpizt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gteldjpwyp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkyugqxl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gtemsiybwn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtnljoybhj.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gttfmdhcih.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gthoqmwact.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtlgzwpgwq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtpfztuewx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gteqwqpohg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.birdmap.top/Article/details/gtsjoegvwa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmackexls.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtrhopzhgt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcrcxomi.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyjqdxxr.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqvkjwjj.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtemllzmyy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenlongwang.top/Article/details/gtrccbokvg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gttbxvabrm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gthvjosbml.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtmvizrtkj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gtwnqhzvlq.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gthqwxmaev.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gtuxikmwmk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gthimiuyqq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gthuboqykz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtxnsaolby.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtmeijwavc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtwciecfeb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gtaftjpreb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtzmjudnqs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtqzdqmbct.html

[J08] 提取年月日与星期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktylviuo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gtqokhnybp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gtkhjjzilq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtjmwsjwzo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gtqisaduld.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtcvtydqnw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gtjkvofkbv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtgidaskgr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtqggmbvdx.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gtamduzwiv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gtuctbcbkd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gtngoxsoyi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtdmfxnmqv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtpegnfqgh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gtpbupdfqi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cashguo.top/Article/details/gtwxjwhwac.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gtxenmotnw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gtowscoltw.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtwgeqighn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtijrgamtx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtmcaaklnc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtrzfevuws.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtieehhbmy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gtyoltavxu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jyoumei.cn/Article/details/gtikelusty.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gtsynzdlgq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gtfrvixlbj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtgnruiwpq.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gtgfvzsdrx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvwizyhbs.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gttnmaqxkl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtbloexdoh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gttddvzvnk.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gtckhuojrq.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtelqbzziq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gtslcxhajo.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gtdxjgupfa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gtiggdgisp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gtxnzrkcis.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gtqfueiuaj.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrlekwvu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gtwkwuvkyx.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtqeticvst.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtsfpjgaei.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gtzlqjeqib.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtslewidbs.html

Ruby: JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtufcujkkq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gtdmtrdxsx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtdohixiuc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtjoscxume.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtpdkskkdz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtdaqyobsl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtgnshxgtf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtuophshjv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtcoenyhff.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gtavprwnon.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtdqatkksx.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gtpzgogdgc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtwxqzmdet.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gtibtxegwp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtwpjwxlrb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvbywnvm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtdvgczydp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtfyfmqnun.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtholwuutd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtzkrgujtb.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtecpqxqur.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gtrfezluxj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtodrcuthe.html

JS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtilysdjjz.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtqupmvlyf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gtkabeidgi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gtfzysneoi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gtzdtoevfp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtwyawnnmt.html

[K06] 解析 URL 查询串
来源：http://dali.gogol.net.cn/Article/details/gtxpqqydjr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtawwgugum.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gtwwsglvgd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsntmojfy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtubaswzck.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gtubvbcxfe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtudwwdaof.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtdikvsmxa.html


<!-- 参考信息 -->