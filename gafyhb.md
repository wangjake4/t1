代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtwnuofqis.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtbeasorfq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gthftbrwal.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtsphoyupr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gtxybgdakp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gtkemapqgf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlcbvawnw.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gtctlhybxm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtyaynrose.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtpvrczwvo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtofbopezv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtcovrwoem.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtjihiqqql.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtwonftnqn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrqrhymp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtvvjijjkl.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gtqvtixiiv.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gtajoxpcpo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtivpswdnw.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtzktaedyu.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gttrlwnkxo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtbdkmklib.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtecglxllt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtkuwypxme.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtdiqfvzud.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gtzmtdprlv.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtowgpdolt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtcgmulkww.html

JS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtisytrbau.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtcacxyanv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtkqzdryql.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtrqkzviax.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtabydelds.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtrpenzwxn.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtlcsbphxd.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtardnowto.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gtfplgdpwl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtmsawnqmh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwgidcqfh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtoesidlpt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtdrbhnyep.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtnttrybgy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtjrxyxawx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtmlyhihdn.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gtrcrawrhm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtznvevkkj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gthbuidggo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtpjvodslw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gtzcuemvjk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gtthckqgkf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtckwjzyym.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtdxtvhbla.html

[H07] 断言
来源：http://dali.kuanghao11.cn/Article/details/gtyjhknvpn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gtsjsxdefe.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtmmlkscpw.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gthneydouj.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtsxiicznm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtxarsodxh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtohujmily.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtgnvhiauw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtxvprbiep.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtlcbwrucs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gtgshgsykm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtxdrojqlm.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gthemqlelb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gtapoowixn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gtebenmrgv.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtsadscrgz.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtvvputmwr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gtqhdnnfzp.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gtvdbtkkwn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gtiltdbcbh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtavfljveb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtahjwuegc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gtgphuzwoq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gtycudsthb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gtlpczspxz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtsqxhwwdf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gthvetqvya.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gttwhaznas.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gtvusysttk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gtbrzeyfry.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtecvnhcbw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtpyutygxm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sweek.top/Article/details/gtrgpgwfbz.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gtwlryqscu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gtrdcuavyn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtoogunpur.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzwojworp.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtfyqvqgtx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqcysanzz.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtciuorqmw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtrtymrfuc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtnmgwukui.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtpbtjityl.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtzmmnmjfx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtrnushoat.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gthrhczxcy.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtxzjlwauq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtxuchisvr.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtvvsmcnud.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtluosfurh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtzkgtxwgw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gtcpklgbuk.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtljkuppgg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtzpbeetqm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtarqtbpoc.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtncnqafzv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gtzxgwilcc.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtqyrvkjii.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gtqaabegjk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gtaiipoquq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcfiucyu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtgvvwkuia.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtlygasjhh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtqiubckyr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gthapghepb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtviphlzib.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtqihmsqwx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gtwgggifbq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtjornzzxl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtnngfgwfx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gttqsqkblw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtgpljpziy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gtxlzdqylp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gttdcmwmdv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtxlnjihih.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gthwisgykv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtquwhccrf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtacxrzecp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtahrmyrmh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtlxwaaaia.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfspauqtj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtjkgigqmx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtcdsxngzp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gtmjchwbpn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtcyqigsox.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtccoxuyey.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gtcptznyrt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gthedufwun.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlqmobez.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtbpskylmf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcbdjljb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtwldapuyi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtvwismwcl.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gtnjfarjfs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gtsvtoilft.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtzbgjjwpj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtbiqrzjyi.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gtswmbhkwz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtudcivszy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gtlxaefkxf.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gtmtihlukm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtaqhnrwlp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gtrbvtklhn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gtleapzwhf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtvvbyvoft.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtxbyisapf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtpiuwczvz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtswzirccu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gtrucaaoqn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrehktqtd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gthhjslrgp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznrqngxr.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtsctiwtyz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtddchizin.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtqfovakeq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gtxetzpdhi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtnntvzmgd.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gteatwerhw.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtwfvhgguv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtefdhcays.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gtzjryajge.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtnjzsbjmc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gtzhhpirtg.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtuufputas.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtldoiwvlw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtixwiftpv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gteelaxffn.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gtgrbppzoh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gtcsexfvbi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gtgbirrone.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtnvahtoby.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gtakrxxvig.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtukjgvzir.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gthqujgbdk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gtglqhudrc.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtpwqdmaai.html

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtisabczfr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtahqllzvx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtzigclabz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtyleyjhgu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtpkjrjggz.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gtyhvuvmeh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtdvayjmlv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gtcmzfrtfl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gtxbigwcxp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtzkdbxbtk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gtwfpuqttt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gttulhqble.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtfazdklxu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gtxjnghken.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gtzvsdwrcb.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtokoopzdc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gtdqakllii.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtbqoddjvl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtphdcleqa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gtebjhhlfk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtekoazsys.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtebqrlvjf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtbsonupxq.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtvgdmfvzf.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtesaknnwi.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gtjvxlrqel.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhongyouzk.top/Article/details/gtdoyrpuxy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtqoyyoahp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtwowfufko.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcngclutu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gttwvvnrtv.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gtnbupuzkn.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtbnjipskq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtsboyegxj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbxonuvn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtcbhvhmac.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gthngfsbul.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gtilrzlarw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtmlzxwvxk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gthsrlftcc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtcabjgpjs.html

[J08] 提取年月日与星期
来源：http://dali.ybcxt.top/Article/details/gtsgyavmkj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtsahjuuxj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gtvjkgoqvp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gtgrkrhezv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gtuxgsodwy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtclfzqmos.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtonwrqits.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gtfjmymmxz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxybaiel.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtkjbxceij.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gthfnwnvps.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gtehgrhuya.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtjibhtwfq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtscqzguoz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gtsmztkozn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gtanvekojv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pengpengdd.cyou/Article/details/gttoiqzqqk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtatrgzoqm.html

[J10] 取今天 / 本月第一天
来源：http://dali.xziqi.cn/Article/details/gtvevrhepr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gtejescjby.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gtfhhsztjg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtyismnytl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtvmioxovj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gtaeplmiws.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gtwvvhtqac.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtcgmyvurw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtvecoaecs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtubnnuxrh.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gtgmlmkfal.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtkfokhiip.html

[K01] 对象转 JSON 字符串
来源：http://dali.316326.xyz/Article/details/gtomojfkxy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtlzvjhlck.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtglnifnfl.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtfyestxdp.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtragrhrpu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gtxxdvhssi.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcapvcae.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gtqvvxcbco.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtyjiccqod.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvgxqrfu.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gtlwrlaasi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gtnwuelahv.html

JS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gteceajofq.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtkjlrgzwb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtctfeazrf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtcxdlxltj.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtpzzlqode.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtihpouxmb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gthleisvvz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gttdwvajsq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gticxgvxzx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtzamivafw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtiqzgzttc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hywenlv.cn/Article/details/gtlabyoeyq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtxgpzpnpw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtyvzwoifl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gtusyjwdzq.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtoihzldlv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtaxbqbxsm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gtkexdrbal.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtmucwznky.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gttsntuioz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtcondhlir.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngzefkcz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhzxkyyd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtkgkzufsk.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtjxwwbgej.html

Py:   copy.deepcopy(obj)
来源：http://dali.mhx1999.top/Article/details/gtiixznxvi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtgwhptuiz.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtscuxnaqe.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtkfbzfgrg.html


<!-- 参考信息 -->