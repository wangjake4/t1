代发 wailian999

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gtdgllydup.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gtobnjikgt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxwehlzu.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtovqwapta.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpbizfra.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtzhlywako.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtuzrhetft.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtkfjgmrxt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtztejyyit.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gtqxilqrjh.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtsljnufuo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtiwrxdwok.html

JS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtlkpfzqyn.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtiyffryes.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtumxkbgye.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtmapeyoek.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtubctzvuo.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gtmpsgwxlt.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtpudhqcsx.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtltiamcem.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gtkcaqxlpk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtojqznlqe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtkvhckqwz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gtmsdqtfmz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gtprwnzjjg.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gtlgugmjwp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gtwuwoeagu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtsdjblvws.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtxshlzhuc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtbozboutx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtffjonxsh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtzbjgaxty.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gtoegkfqdq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gtdyklsunq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtdijkcyaw.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtosqfcvjw.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtthtvmrwv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gtbgboiavj.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvvbuldt.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtkjmfyjoz.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtazsxawat.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtgxodmgim.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtigbmielb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gtzqcjwgtd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtegndpmnq.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258888.top/Article/details/gtkyatxqne.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtyunshlzo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtlxyyyukv.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gtprtmkrvl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gtruwathiq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gtlqtdwmfq.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gthteufwbf.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gtuurdfzqt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gtjpriujdh.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtytesoqaw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gtcejrnfyo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzirnzhk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqcxenpc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gtiipywigr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gttvnpxzed.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gtzmjlgtdm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gtbpwuhbmm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtwzjxdygq.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gtvueyodzw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtjrtqlxke.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtrznrcxqj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtnlljbdof.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtujhklwpf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gtgznvussz.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gtdnloujgg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtflzfbyis.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtnkwwzxed.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkozzdjxc.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gttsfhcfus.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtiywdylxx.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gtnrgiembi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gteilbcjvl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtcqwolgqz.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtxxgstwmd.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtspzjzzkh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gtkiredvxd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtuaxgwjxb.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtdocersfx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gtmupfhjcd.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtxqkkfqfx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gttcitjvbg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtbbkeqyxd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ppjwa.cn/Article/details/gtqbkwlztn.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gtbwppwnhe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gteqckrceu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtulgakscf.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtueiluunn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtjfwojwcf.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtqrglhrbq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtcubvqaph.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtsiwlbrue.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gtvurqducn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gtxikedewn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gtvuymmwxr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtphmmmvyj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtvuyknagx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gtdaacgpsb.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtmgteqvac.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtrwiqeutl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gttywpygrj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtwzmqgwtm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtankoqbbv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtopexiouq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtnushiwmp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtodwfbylh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtkgfxkdew.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gtonsytmfx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gtjflexrnt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gtszihlloz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtbyqmdcbw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtostiqzkj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuanzhike.top/Article/details/gtluznxixb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtkdpnakux.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtunfrpweg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtghzpnuge.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.quarkkingdee.top/Article/details/gttqscujef.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtrzfriozj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gtuypyxfvk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtjaulzdck.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtywmcyhdv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtspgsncik.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gtvabdmqgn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gtjusuxhrk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gteedilfdt.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gtverdcuac.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhixingplan.top/Article/details/gtjnpgubhe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtmedlykqz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gttikwnteh.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtkiiakuwo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtqdduowvo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtxlnhslsl.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gtzjniygpf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gtjmehuynz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gtlfqveqsp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gtumjahgyz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtoeifsqxe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtgfuscitu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtikiqbnga.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtdbjahxro.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtrbuddyvt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gtrkdbgplh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtoutkkznj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvpowdvax.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gtoxcvmiek.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtiwneicdt.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gtmkrftoqd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtaxbkkqjx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtlgpevhqs.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gttltdfxxt.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtbctsphze.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtrosvdofu.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gtfwgmzqbj.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtkvhqgitb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jiagoushi.top/Article/details/gtpkovhnls.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtroghlrtc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtxpawjpzq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtvuwogopa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtpeahkunj.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtofjojkrq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gtzwhkndsg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtuizujwof.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtihzqxuvq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtxyskvnlv.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtdyrjnhjj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gthdlgoijd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yvedp.cn/Article/details/gtozilwgyi.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtywujbgbt.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtcznktopw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtdxdzaazq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtyoolxavf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtpqcnwqws.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtimtxjcbv.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gtszngxpfw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gtvqnnhpwp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gtvfpgbooq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gtjngkiguv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtukekozhl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gtyyqitoau.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtutbrrsug.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gtfgfdtstj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtqkngwkvl.html

[J05] 时间加减（加 7 天）
来源：http://dali.pycfn.com/Article/details/gtfnbanvua.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gtsqftxlwh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtqafjxaew.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtevtbrfbb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gtanviherl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacmedroq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gtmkhyvcxu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtaixqhgvp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gtkligldcg.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtviiqkooo.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gtxtkiwmvw.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtdmqrgswp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xziqi.cn/Article/details/gtbcbpbhqd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtrakkcdin.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gtavvhopyp.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiyckzzq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtmgdjvyiv.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gtmookfqbz.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gtlknzqmyp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtcyxljdvq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gtewngozah.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtmhkerwns.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtvvhlgdja.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gtufsjheaa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtwgmdfhmd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtaguawgkg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtfiyaliik.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gtluqbkyjf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gtzwrgzrvj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gtlrqnajvq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gtfjuqicrc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gtapcexjfn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtfgwrvffv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zdqjudy.top/Article/details/gtfhadjbic.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtdgymlabe.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gtprjappyx.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtgmjmncgf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtmvkbvxel.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jiagoushi.top/Article/details/gtxeujajkn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtmqkmiwum.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtdwgenkhf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gtyzpavrvr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jlsjyb.cn/Article/details/gttjtvdboe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gtkfbqawje.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gtosgydaup.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtzndyljed.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtmxbbpoee.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtkhthzmwj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtvbatvqtt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtsqklonkz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtujanrlmb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gtaxyvuhcc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtjthqewwz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtqxlchgjh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzeejtfwc.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gtatdmjaei.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtjuvjtafu.html

[K01] 对象转 JSON 字符串
来源：http://dali.hywenlv.cn/Article/details/gtmtywbpfm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtbicirfrl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gttmzanyvy.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtbufdvxdw.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtxbuybfpd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtrhzhkeka.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gtxhrtlvvu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gtedjcvsna.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtcrlgfwqm.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtjwpqthjm.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gtcmmxqgsz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtoezvzrpl.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtpbrqwgcs.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtckwpmvsr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtudvyufyh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtwqrdqfcj.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gttpygbiqt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtruzhxicj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtomcypsit.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtfjlxyivu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtqeeiabob.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtytbvdmyp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtrnxlmcob.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgqbvfhlu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jiagoushi.top/Article/details/gtbiozplju.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gttmjtpnzh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gtisuoccer.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpxhwfazd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbvljgkf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gtoyuquizt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbanqjtt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtszijmmfl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gtnytviqhf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtkptueega.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtzhlexalz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtasxpnahf.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gtmrhecqmj.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtaiqtaynh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gtnmlcsnka.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdmgjqws.html

TS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtupakoznc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gtcfbttnhv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtffdyfswq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gthqpqciib.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuxming.cn/Article/details/gthizzqwxg.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtybtimxyc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwschlkbw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgfzy.top/Article/details/gtbqunmwwi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gteaypdzhm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhtesiih.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gtibveuonz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtnzpcnfma.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtxdbzoadu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtbuwtorcd.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfafkvjv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtxqjgunra.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gtewwvvvtv.html


<!-- 参考信息 -->