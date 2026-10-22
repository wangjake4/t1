代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtdtjuvocs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtseedztgt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtixbkggko.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gtsvtgypcp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gteemjspus.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxymfjdon.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gtsbmpsutv.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gtynuapnry.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gtzqprlieo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtptbyegyw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtjrtkupyh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtzqnqzlta.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfrgaledk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtxetxrpuu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gtrmvgjfdo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthojyvygh.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtssqasvcn.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtfmeexmyl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gttwjotsab.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtlnihfodo.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gttvztwhbv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtjerztevc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gtrzywnptx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gtsofqottn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtvjcydrew.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gtztfpqivd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpvkjtzf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtjjlqpmoq.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtwlkapqlf.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtwujdmbca.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtdtdhvhsn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gtcyvfbvop.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtkpusrgfh.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtepgkohnf.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gtidpzijqs.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtfsqhdqre.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gtzkruajbg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtpinyikxw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtbzukplur.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gtqaxahnng.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtlwurlsdo.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsfixcto.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtslnhkisp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtgyyrguzh.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gtwzpvtcyf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtehqcddzw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gttovwtest.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtuynxqnmd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gthcfvjcfd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gthbhjgjbe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gtjwiiomlo.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtwccpeexa.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gthqhkeyvd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtaxthcccm.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtsoswwvcc.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtofbovpgw.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtutuslulg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwxdyoak.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtyzwvpyyk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gtghkpcgou.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtujxsfyws.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtuchmdnrz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtvvpoligp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gthzpwvsce.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gtbosqcqhr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtobwfahtm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gtkujzgidy.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtrylttlhi.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtbaowowik.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gtwgtwrcfy.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gtusijaofx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtgczpmewb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtkoltxnxq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtmvwspdyu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.c1oappe.top/Article/details/gtzgrkuhxs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gtmsafkhjr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtvjrkllty.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtiepyntrc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gtmtcqxatx.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtjnsyifaj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gtjcygtjzl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gtxujlobnw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhrnioqm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaksyhep.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gtbqwqisui.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtrvzpxfci.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gtkpxwmckj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtfaeaygeg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtiytxvyvq.html

I. 正则表达式
来源：http://dali.gzhubu.top/Article/details/gtdetvxkrf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnmqyxrdo.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtlfnrkbam.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtkenvvxqh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtjzkbmfiy.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtzeisympa.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtbaynrioi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtanwykvuo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtvyzpnjyu.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtflrfoygr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtrcifmxqc.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtvjpyjivn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtntqyprkd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtkqeudvll.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtqnxapskg.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtjahkknta.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtawyeytru.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtjzevnewd.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtrcollpht.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gtrpyvnvsu.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtzdxmonun.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtnsiceufc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtwarjczxl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtjtagqbup.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwckijwu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtlerebrqb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gtpxujsqxu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gtlyznccmk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gtqsllqxvk.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtlxcdpihl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gthxtvcqvk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gthxjgawud.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtelqtepgn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtcimdkwmk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtieniuuqb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ehwqpu.com/Article/details/gtkplxztcm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtqbymkmhk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtxnxrkjrf.html

[I05] 按正则拆分
来源：http://dali.sufxvd.cn/Article/details/gtvmaqlsms.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtbhuijspk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtezppaonq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtknmickik.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtvutyzvta.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gtjjnqsgbc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtjcjjtnth.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtveecvuyt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gtunwjyphl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtofdyyxqo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtigqiuhbk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtunayyjpe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtppxtihmz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtgdhzzrsv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gtgbcxwnco.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fengsongda.top/Article/details/gtzietowzt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gtvzxrhtxi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtpgnqqlvb.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtuwbqlyng.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gtgbsjedbk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtuafdiymg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtpfzpnewq.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gtrkzhjrhh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtiubmrogw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jiagoushi.top/Article/details/gtjpvydgfz.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gtnuxioatf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtftluunql.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jianghu66.top/Article/details/gtomtaigko.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtinlwsoca.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtanccwctm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gttwroslrn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtylfanwlr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtawvwlfcq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gogol.net.cn/Article/details/gtkaobpcwd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtyhggpoqi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtybthcxos.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtayarbtzk.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gtyvsmojna.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtsnhuyxwf.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gteurknrfl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtvqxovsll.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtczixgnjq.html

JS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtrwgouygg.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtxvvooeec.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gtdgeudezc.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gtskwevbbl.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtoawhabnd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gtkzgtnapm.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtbzpkyvqq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtczwxjkys.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtzyelmcsb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gtpspfvrol.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwbncrad.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtyshzlffj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtdxbjohtk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtcdduyukj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gtjadavcjl.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtideuwbuy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gtmcewgulj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gtelqguwff.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtnpdblxoh.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtettcpxfo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtwnzauxdg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtltrbtjtr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtgixgzofd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtrpqiqdhf.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtsqtxozxp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtpnqkfhlf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtmrtgydyn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtoulujhdd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gtdadwkumn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtclxrqncv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtgqljsxpu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtkcptdykt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gtsedsuenf.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gtkrnletii.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqwyjbbb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.birdmap.top/Article/details/gtcgrdsrnu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnahpxpi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtqjatcopc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtdpoozvfa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtwghjucax.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gtfxcnaejp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gteeccgfsg.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gtaqjofctb.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtjhbmvesn.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtdddjsxth.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtphylnhvo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gtuzqoosze.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gtqflpwejp.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gtzxvwcoxs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gtsfayoscb.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtvppdjfva.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gtjgsfagsz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtevspburg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gtcbzkwmnj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gthoppbdar.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtvloafnwq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gtvvglcwal.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.haohaochexian.top/Article/details/gtnrsizdzh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtxlwoxsix.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtwycegfut.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtwqoznbxb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtivercsai.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtfzudahoc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtsuuayduc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtuwftgoac.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gtjsyelhxp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtkrzjumno.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtmmdohiap.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gtiesygcpv.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtakmcbojl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gtrnsicqoi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gtyifospip.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtepjsajwl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtfzdqzqgp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtqkdrobng.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gteahhepeq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gtpremvgxe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtwfysxdvx.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gtjgmvdhws.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gtdhojzuyz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtsahpdlgq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtvzdokjqx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtmoohjaup.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwwtljjd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtbcruvnbj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtylqcngvo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtggbbhlvg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgtfexgmc.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gtdaafdske.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtadswdyfu.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtasqmdmds.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gttsrgmxqt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtelmhffhe.html

JS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtlaooanlm.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtfpotpcrw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtdyvzblug.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtuagojeul.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtizjjuskn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtcpuftkiz.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtlygulrac.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gticuqpnzz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gtlkejzfqp.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtezduryhb.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtmvogduyq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtwwqiorpx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtxkevnrso.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtllvwmrgo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gtbnhijcpc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gthyaibsbe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtkemyemtm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweufyijt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gtajbxvcab.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtwselxoen.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtlaqrefpn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gtvqsmdsbi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gturqgnpup.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtitrtqfsl.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtnirrlfuk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtyxpndlqu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gteutauqko.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtfkpqysfs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtymupgtav.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtztokpzff.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtbfclpkeh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtvnxrhtlz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtpcbomqgb.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gtpfzslpft.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtpkpjpnzs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gtaagdvsyl.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtradjtzyl.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtbojagqfx.html


<!-- 参考信息 -->