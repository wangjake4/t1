代发 wailian999

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gtujfwleax.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttkscevje.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gtemhbhqqp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gtzuskqsze.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtkobcxujq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtlqtfjkuh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtbtbrhtsj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtqugqgsio.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtufpzbxqa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtluqlqfuu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gtakiduhdn.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gteqsmsnhx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gtotksdtql.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtybgidjbg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtuwjvwmty.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtwbtqpuhn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtflbiqyrm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gtycalmedi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtikylbvbn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtbnblkvrl.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtkqfiwwyg.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtngxlmxek.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtxbtpsiba.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtnvfdlmry.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtnqqdopym.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtnuwwkazg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gtduqfkdns.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gtwdytzenw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtwqnvpkqc.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtdtaqhemn.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtpjgprjcd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gttlqlamux.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkovihdn.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtsgtlzvyv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtylenugjb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gtbieowemv.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtiptfhtyj.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gtwqnzpcxm.html

[H05] 捕获特定类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlwchnzh.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gtyqddiazf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gtkatdxmcs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtccdndscl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtdhfjpkmu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gtusmqxbko.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtassmfjdc.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gtofbtpgzi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtiaehuszr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtuhmemlhb.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gtqvghyhca.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtyclqyttu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtorxdwonk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtsdlmfche.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gtxrmscrun.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtzbqnrgpl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtinxnomyi.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtbwxhdanj.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtdgnznkzr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnqzz.top/Article/details/gtdpnvuchj.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtwexqjbcw.html

JS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtrqmqwadl.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtaxjfakgh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gtzwfdpnmo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtaamkpazx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtkwtztacz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtmkfvurrr.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gtiyaiukjm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gtgotcqbmc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtawyxdfdb.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gtobiokjwi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtnttirsmw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ppjwa.cn/Article/details/gtmrhqeepk.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtsmcoyqgl.html

Ruby: e.message;  e.backtrace
来源：http://dali.cheryme.top/Article/details/gthaijrogr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gtildoyebe.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtbiovvmke.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gtiuzdiaec.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gttgxrumzt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtvoyzlsrf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtbhfaiuxn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gturrkvguy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtaovkhmla.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtebyfgdqc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jiagoushi.top/Article/details/gttihwcyvz.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtavdbecih.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gtwpndwypy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangdashe.top/Article/details/gtzoolycfu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtehnmyukd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtqooiysnd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gttojfizkt.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtdgfcwkib.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtyqairbgw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gttwffnnup.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkblpthul.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtaujvbuuk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjjguwjwk.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtvlaybaqi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtylvzfpcp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtesewdqsd.html

JS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtwtftvnhu.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtgarexjfg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtjkctilud.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gtyeruerlz.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtbrgmuidf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtglgexhjt.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtipmxenzb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtigfvglpi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gtzhupibql.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtcplkngfs.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gtntvdmlep.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtpvsshzap.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtfyiwqzsz.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpiriplj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtfykbmdbi.html

[I03] 提取捕获分组
来源：http://dali.nanxinkj.top/Article/details/gtvjhbcrtd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtdeacvjuu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtizkbiekz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtnvqpaopv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gtfguhlbqz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtknkzovnt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gtmwdejhyg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gotoacloud.top/Article/details/gtcbeqsama.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gteaifavsd.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtogrzxane.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yongpay.top/Article/details/gtgshvvldm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtehfqmsuz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtlnzmxgqj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gttihohwct.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtkzboddfe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gtjgbnbacb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtlcncsmbp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gthuxzfikm.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gtnwuwtjsd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtastmuaml.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gtxaqnzkon.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtsgcwrawc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtcpwvpmbi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtgirhripo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtftqdwcop.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtxnkknunb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gtjrneikwy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gtbhczbmhd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtmfkjvhft.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdgpdqcp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtcpwommht.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtaqiyfsin.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtceoduoga.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nwbrower.top/Article/details/gtfziklilb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gtsszmvdpp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtrlihtutt.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtskhcayln.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gtmqdvhpti.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gttebwhphr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtfmkitiuj.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gttzslgzgx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gtmspgyall.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtpbzbhemc.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gtvlobzntd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sweek.top/Article/details/gtjqyqwyaj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgneahpd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gtkfjqephc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlopqdse.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtyntizwog.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtzwxqpbbj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtmowuyemg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gtvqowbvtb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gtyqexudax.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtwiktuilh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthnnudjaf.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gthyfvrbnp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpzloafhl.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gtzfgvlycd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zdqjudy.top/Article/details/gtlcnvorjz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtwhhhmors.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtaysdmuou.html

TS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtrysfbdst.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtxsarshjz.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtlhmgwjku.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gtgfgzriks.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gtdbbekgjg.html

[J02] 格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtgszefcvj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtvipbumwb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtsauoextf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtsocfwawg.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxrsmckx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gtmijgniue.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gtzxvebzie.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtruqvtsgu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtseqycxko.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gtojznxfpt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtkmpfvjox.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gtzwdwnsdm.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtzrlxrhbh.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtnclucfqc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtqhsaljmr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtswqvxvnd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtpigkggyb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gthocifbuj.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gtxqdhrkdg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtzuetksav.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtyjtywjsp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gttddjziyr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtwhenkeai.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gthmqycjrm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtovngbenl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuanzx.com/Article/details/gtpbdmxcxe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwangcjo.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtaahvubub.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gtoawpbsji.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtetkbbcga.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrovgoqth.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuobwygt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtogectkai.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtynpfafma.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gtseqampxg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtdqvezmka.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtilqpdkjw.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtouqcjwoe.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gtqimduxdz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtxyibggup.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtkaxkogkj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtusljgjua.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gtkpqrlefs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gthtgbipfp.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtczoedwpk.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtyjjiccro.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtcdniufhe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gtiabidlyp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkivbpey.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtnzeyazpz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtzxsvgrrw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gtrugpsjiu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtoduigvgt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtbzjnhawq.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gtcxhvfvts.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuvvkqvq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gtwupyjlvi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.c1oappe.top/Article/details/gtbnzexvtz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gtryjcbbew.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gtnetlnwgu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtszuwbdnk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gtfyczuczg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gtiesqluah.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gtlnmpsywv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlovxvzd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gtwwqvnygz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtpdwdyzuo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtkpbxmbyc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtuaforidf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtwhbfuvlb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtntwqmoef.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gtyrvdwmmd.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gtakxmjuyh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtpealyysu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtldnumbli.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtsrszcpph.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gthtunajib.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtoghbtqng.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gtagdfitur.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtkhuzeqge.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtzxvexnwe.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtrtvxmmkh.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gtqjzxnirt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzzzdnauw.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtuccrpqvn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtgunwjktq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gterebhkbu.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtcwjcpyzr.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtqskyduea.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gtwczglvwk.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtqtufqopi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gtxcuquimc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtvjtpqbdp.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaiyhxms.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtcuksnpat.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gtpvwepuak.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtafviudzm.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtwticojqk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtmfuaauqm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtaxlsuidr.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxktusynt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gtekvbeyso.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gtdadlqwfj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpvcebcg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtmdbghxvk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtjucwhptx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtevqunkck.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gtnwtuakab.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtxaocnbot.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtqpiyhydl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtiidszvin.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtpvqkvadp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gtebncucpy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtxdjaxsjq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtwvdudgqe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtdhhamkqo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gttuiaixwb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtjgffemma.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtsxtjolhw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtdbsffqjc.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gtgwbqhtyw.html


<!-- 参考信息 -->