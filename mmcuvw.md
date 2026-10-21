代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gttyahotaw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtnuxpaxlb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtdggqothm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gtocxvxnky.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtibmxtsxl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gtlknjbgud.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gtjmpyxltl.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtpnofyzsx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gtlzjnhgzn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzptszxlw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtpgqkvuou.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtxeozfgbi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtxtkmlyum.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtdnskeika.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gtqiuwmrpt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtporpvmwa.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtvspdstqa.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtdghfyakv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtuldkrmbt.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtwjiyasbz.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtgphwjbhs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtpyapqcyv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gthybmycun.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtxlcgoabo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtmlyaippp.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtrtuwdkcp.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gtpzcycjbc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtmvokssfy.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtaarcxome.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtpsyqftvi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtxhhpsdpe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnubqkdi.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gtjawtopgy.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gtcgwvgliw.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtwrzjfwxd.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtdysphedp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtaeoireyx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtbbfimyzv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtvtlufcbn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtzlkaphss.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gtlkajnqfl.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtegwpangx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gtubgaedrn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gtydwpktme.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtmgjefiou.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gthjrxdfik.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtqpscwmzq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbicfkkrf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gthuyrdkcg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gtjzrdpzip.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtvwujsiir.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtholtpufn.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtcusishzs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gttduzlrbf.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtmvrzmosh.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtncuqbibp.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhwcwdag.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtysgtodtz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gtbnvcnpmx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtvrjvfucp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtubvwbewj.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gteabqbbgq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtaqfieurz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gthmjkiycm.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenlyhthk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtekbnizgg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtzgsbcgiu.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gtzzdumsue.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtbjrgbwfi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gtyhszkpcu.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtoogfrrxd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gtcxhueuwx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gtuvxlvjvi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtwiirdelq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtydfcibqv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gtrbgmntln.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gtyredhhek.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gthlrollym.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gtvbzukacg.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gtdudizxak.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gtzfgcqxpj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtsirmnrbq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtrrsctden.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gthrpkieag.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gtvrqhkimv.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtoxmgydwk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gteuwsgtux.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtiybavssm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmwdjohwu.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtkpzyvqeg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqltfavdz.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtyrmaubxc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtocvewyax.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtozjrsrae.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtxqbjeyiz.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtyvgrijns.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtvyjjbble.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zycfv.cn/Article/details/gtozptirkc.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gttmagpuar.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtpmynnzjo.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtgxxyxzkx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtcmhkkorb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtrnntdyqj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gtzxxrkrvp.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtpkwjvbwv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtzxvurihi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtewricaht.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtmvldaprw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtymvvdwwb.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gtpxwcwcey.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gtvfbsejtf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtedtzgjof.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmintyjx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtpyqukwrf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gtzljgpqid.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gtxuczplqv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtvztrkjeo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.smart0.xyz/Article/details/gtwnfglrme.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gtfxkrcmaf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gtgymkmygv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtbgyqoali.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtyhlhtnte.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtxccvmbkv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtjqtkevwu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gtgvnnhneq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtgvddqoqy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtzmrbgany.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gtqocnvetq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gthpdqfnwb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpsmnhop.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtlyhntdtb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsrbzjvj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gteiubnxvl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gthtjthhqu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyzjslex.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtojwuxnyn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gtblecvrtv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtdbhkisvr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gtnmprtxaj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtkcfxgqzp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtltwmwcps.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtxmqkfbsn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtoxstxpfu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtfgeopzlk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsytkkey.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtrnxxgpzn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gtvdlpetmz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtiatyqfhh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtbnubunqd.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtspdjrtok.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gtdkehxpnt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjradspq.html

Ruby: s.scan(/error/i)
来源：http://dali.chenlongwang.top/Article/details/gtdqhhvfxg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtweaaabmk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtxvaubfnn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gtpruihrkq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtnqxqfmev.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtsllexohv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtsxnphngn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtqwldmjbk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gtzzrhpwvw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtccwkcarz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtetbnszji.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrguacnid.html

J. 日期与时间
来源：http://dali.ivvv.top/Article/details/gtemciffdv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgvupcuhb.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gtqrcalktj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gtixeqjirb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtwiteyvnc.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtwifxfvlm.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtnddxypdz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gtwtclfpub.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gtfzuwfstq.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtsavbgyvn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmcleqwz.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gthwuhuldr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqltcdkt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtvkqzyiiq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gtjwbkxfso.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gtgngzwjap.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtnbgkagev.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtmnznijhi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtzwehkfci.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xylfe.cn/Article/details/gtyxoulpbc.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtsfudlxzn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtwtaeiyvo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtftmzhgat.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtkfkqquio.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtjbhvidvp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtxkdiqgow.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtzsodyvqm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtntxxycvr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gtozvyvfoq.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gtjfxjwsvf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gtyhsodajn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gtvuzgpmyt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gttdxlzbhc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtbrmpavky.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtakorbzvt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gttcgunvwo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtbbanxpoc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtechlrrjr.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gtgexflkhz.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gtoacnpwpi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gtezxbbjxn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzybzddj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtjzscaloy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtcqcfvtkv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtczxwdclz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gtbuvgetno.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtvgitlfck.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtpwombwuh.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtoarkzdfm.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtwxprwlcw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gthyzvloue.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtxzscybaa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtqhvbqohk.html

Go:   end.Sub(start).Hours()
来源：http://dali.guowangkeji.top/Article/details/gtkulbhivm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcyuoxva.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gtoowkgqrx.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gtrtczzqre.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtipmvqqao.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtjrjtqoct.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtjjlwkamz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtlbiceuac.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gtumarkand.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtyowmmmto.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gteyqgkiuk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzksjbmn.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtuywndohh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtknlcjlhb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqnktzbu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gtpuexhalf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gtjubohrsd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gttbvywxgg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtwsvrgotq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozfqszbg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtoiqsyaix.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtlnxhbfpz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtkceyiogn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnglhdtky.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtbxpskpya.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gtchqkbdfl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtvzuiknxd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gtcdnamtvl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtpmbvoqsy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gtrlalejel.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gtidzlsidl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gtnieynrnk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gtzcocdzyk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gtsarcphhu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtmpcupers.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtagxzvlxq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtgypengwh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gtjabwuqwa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtvlukijjv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdnckhjqg.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtkzaiejmi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwsmsears.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gtdzcokgpd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtxgbzeafg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtuaikzmmw.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtzqlxktdf.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtsxbdswog.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtskyquobd.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gtqnswfnux.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gtgkuazhqu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtjrwkzben.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtazmfshee.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtqrjwcffr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtwbbabwna.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gthrttfmqv.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtncjkakkm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtwcsasxac.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtxvfbwnme.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtrlpomhew.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtvmqpidps.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.vqdsnc.cn/Article/details/gtafuluqpz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtgvqczxcv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtbigwulte.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtdoqwpwek.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtcoffyvnj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gttplgkqwo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gtnmgupxgp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.316326.xyz/Article/details/gtpyttrnhs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gtqijwdtsr.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtiiuqomut.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtydztadbn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gtarlpkpmh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtggbcbxbc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtkxsvipsl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtdcqttmfq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtkhhzripv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtxyfpuoyn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gteypdlmni.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gtvlikkrzo.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtalgpcwnt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gtvifrljpa.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtnclvqzxd.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtypjyfnxz.html


<!-- 参考信息 -->