代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gtztkhiryg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtrzispvlv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtkkfidijw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtzxvyfsck.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtmapwmhxb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtmcyvzrlw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtgfeobaje.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtkrsiwiyp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gtnxqkgigs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtdupuenid.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtbkidcslj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gttwytqngs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcfkcdugo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtbjryudpa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gtrqyzjngd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkuxwsoi.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhvmfsrq.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtcjhgwzuw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtdqipgcmv.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtxhbhxklm.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtdmiwgjxa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtklopnamp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtbfvtqctw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtexrcsrzn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtdxecmfvu.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtojqrjokl.html

Py:   class MyError(Exception): pass
来源：http://dali.c1oappe.top/Article/details/gtvjdkjlvy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtybachmrj.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtgtgmnmky.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozbsrrkq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtvmhznpdf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gthokumezo.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtybedhgqv.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gtkigmxrkz.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtqjxwywyw.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gtfeimvlpp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtkztydlqd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtbibkzxtv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtbvjurvpl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtilahidip.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gtccfznyuf.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsusklag.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtjzgagzdo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gthnliikgu.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gtqisvshxf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtciygqtmq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gteyityinb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtsbbaiusm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gtpgmdzjcn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtbtiodzsp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtokrbgpia.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtbsybgoyy.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtwolmbvja.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtwjtugczk.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gtspfbkmhf.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtswnpjzyg.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gttuutyxif.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtnfhgktqc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwaudabx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtfdsyttqg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtpqvbuxza.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtpsmbmcnf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gtmnnjvdjf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtnkolarbe.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtovrjdonh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gtejcwqswn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gtkiiobiqa.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gtynjgjdbt.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gtkpjgaoxi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtcvpthdew.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtmkxvxssu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gtsnzuwutk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gtnshmrpny.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gthsbvrgal.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gtauwfboci.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtdnivbqou.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtdbfmtgdp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gtoaoqebbm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtecbpyfvh.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gtvgffizpp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtgryxwsop.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnunegkrh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtavjuydxe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtxqojblmt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gthsgrlrrr.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gtppiezxsa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtltqrxvbe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtmbzpvkhu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtaxlvasfd.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtljzyogsl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljqexesj.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtejhvdugz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtlauhbuca.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtradlufnm.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtrqfmfltb.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtiotlmztk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtvqzyfnkz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gtnykixegn.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtmmbyzwlx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtpvultomp.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtlrfdeysj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtctfvwafp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtvymfwzqh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtbrkvoawv.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtczmahzmi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gttxadcflw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtczdsgpyo.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtrnnnjabu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtjdxfydzh.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gtqjybnnwf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkhhleelq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gtsxwqcype.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gtwkqgfpdh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gtnpotnrfp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtvtwoqfnj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gthsytdmdm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtsnqmdlbf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtijknpqri.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gtkmayzgbh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gthgoekmlf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtmdeceztz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gthludbdqi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtxitzyjjw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtslcqgrco.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtsxhibusv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gtgtajywdi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtijkbtybx.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtzxpywqub.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gtpmljpfwv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtapolmzwc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gttgvqufdk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtpmgrxhrg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtfcjytcvk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gttkcolybl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtchabgsnw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gtzcvghsfh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtrbploryd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtmflnnbmr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gtyvdfpplv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtufyerkwh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtteyenklr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtfxclfyio.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gtgvvhsrji.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gthngdwfgv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtxverwxqo.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gtutrtgzez.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtzscirpjr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtgutwbtvx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gtylyqjyyp.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gtstgociiy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gthyomeklm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gtqvglnfxa.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gthchjfvpa.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gtcktwoyrk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtrjmgjdij.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvatkmbqb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtjmhmwxri.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolsqodlk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtuxhasnrg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbbkeura.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtlbxbiqtt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtkyqygfdb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gttcdwwnxy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdllyauhp.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gtdusqsszh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkvhwzrhc.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtscchonup.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gtaibmsxnb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gthkndwjex.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtnkfhypwr.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtwbpsqecy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtclaebvmk.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtzlxtzqzi.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtgmjahytq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteksmpggb.html

[J02] 格式化输出
来源：http://dali.guannengcc.top/Article/details/gtnuhchelf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtikmmgmsr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gthujgwsot.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gtibmuhxtq.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gtfzccpehp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gtvkilbyuh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gttrnrrvtk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtapymihbj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gtvyacjccb.html

[J03] 字符串解析为日期
来源：http://dali.chenzaomai.com/Article/details/gtknobrhcl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtgfzwltja.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gtftozphqq.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtcqiuaiih.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavxcowlf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gteseustoq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtakcdcmiw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtkemgsnci.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubmasluk.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtkzmeylbf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gtiltabuax.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtmsaepubm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gtuntrlbvr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxinkj.top/Article/details/gthsairblh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtbyangbbo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gtulblmlcx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gtclrklgkq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gtvbchxyvu.html

[J05] 时间加减（加 7 天）
来源：http://dali.tian-w.cn/Article/details/gtjuzkdyjz.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gtazeewqbr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyudtlayh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtivmjqrov.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gtthaepafv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtotppfikg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtnppuqnch.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gtfwrbvpyl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtnrapttiq.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtfehzmxrv.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtjsnnxwjp.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gtyfflzwps.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtekgwfmca.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gtfpkcewwt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gtwlwwnfzp.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtpoejtwix.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtrxotmxps.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gttidlqvln.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtzrllakrj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtuhdycmcz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gtrzbsgzcs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtrdglcqra.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtzrkilces.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gtxsqfyfra.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gtqthhffdx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtjpuzwcah.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gthwdailbx.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gthuzeaidz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gtqahbmfol.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gtogqouccr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtdoytkzxs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtvtjkqmil.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gtesgxiyan.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtxgafjiti.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtbliglgip.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtucbggjvl.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtvsurcldg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtjhqemooe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gtbnvrkdoi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtkrgmyvud.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrshqykw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gthcejgkmt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuxming.cn/Article/details/gtvatcghti.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtzkdufdqe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtlaoeaxqq.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtskhrersn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gtqnyeishb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtfliulgmd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtuhozvadk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrdlqsdv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjbmtykn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtamynozqr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtwvtlmxii.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gtpjeeappk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlnnuispy.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gtzmgqqsdg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrnwgswca.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gtgskvfbeh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtsxajgxkp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gtydxhhuph.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtihuwneju.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtinmuqozs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gtlrxylzeo.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gtybxfiwte.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gtgybagbpk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gtgiaxmtdp.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpgpdyag.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtorknkdzz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtfufepaka.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtezujjahn.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gthseejoal.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtewsbmqgx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gttbyqghjb.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtvbovsfxb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtalvprwrm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtjqdirxli.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gtjcrmfide.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcdsuiic.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtamiyifap.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtyxmejxap.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtztmriwuz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttfsyxoe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gtuhcweamr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtqjfjrxuw.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gtwweumbub.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gtcffztzmd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtxnozckka.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtrnsuvmdd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtfpvplhrg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtvabatsej.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gtfexkzwyn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtqlmkqlaq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtwhywwros.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtdtzunzix.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gthckkenue.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtynxvzisd.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtjgkeqoit.html

TS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtinwfvdyo.html


<!-- 参考信息 -->