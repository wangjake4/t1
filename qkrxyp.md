代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtmqjncsjn.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtxmzvhbxv.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtolgfstft.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmzovcmky.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtuagbcxga.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gttdobubmf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjikjizz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtmvhimzlu.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtajxtspgb.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gtseuffcjl.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gtouhmrpxp.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtqmncexhe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtabdvlhyq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtqfrctbby.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtqcnhwucm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtosvbstpp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtunotwvvg.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gtqgvxwvpd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gtkdisxfuj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtwkvvsxan.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gtilseosth.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtmxbiushy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtmbeofbzk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwroabpr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gtkfbcsjnu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtyksfpaqk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gtvagbmthe.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtdzzirplw.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtxszkvhph.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnqzz.top/Article/details/gtnddevihq.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtlsgjqlbp.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtnwbjpggs.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtbnpcscsg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtxcglqmax.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gtoqrtsici.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gtfpgwolnn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtyumswbir.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gteoahpkuq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gtifnzftxz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gttatatyva.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtuciyydru.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gthxhfmyxm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtaftxdqos.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gthvqpdmqt.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxvpwhhc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpcvrguy.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtkrxozone.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gttpjxhnpz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtuciocrcg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtratvabzv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gtlciumnsc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gtzrelclto.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtfgwiifwz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtcgtnbmko.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvlhjtlq.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtxlktszro.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtcmjalito.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtxzdxpant.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtejzxyghv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtkxnhxozy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtzljmvbmp.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gthruapesh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.316326.xyz/Article/details/gtpliwrqvr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gtsezrqgcr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwornlwuo.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gtywdtherz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzmmvefmb.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gttshqbbhm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtctljsasp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gttfbtyybz.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtwcxpxv.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtiogjgglc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gtafwnqvyx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqunwhepy.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtyuekytvn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtpdqglljl.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtjikbzsmv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gthotlypwo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyaxulcm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gtquvuvxtf.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpauthjjs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gtunolmjqa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gtacjgbjsz.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtchztfaae.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gtvpdgkabs.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gtqvauwcmv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gtswphqymu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gtdulycebw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycgrvwcu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqfpgikt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gtaxsnxkod.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnigwmdd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gtpbiagfip.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gtoqyeewul.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gtkqeojdrx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guowangkeji.top/Article/details/gtvpsrjujb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtosrufdmy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtyquxucpc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtajzynedu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtjxkkiebh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtnamlzfkl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtsriatzdj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtehzmisyk.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtxuithadv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtdbgitdtq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtailhnwyt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gthnxttija.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtvawbrbdx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtxgrrqdah.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtdfplvgsz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrhekfgp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtusleokca.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gtwdangawx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtpstthqap.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gtgplpqhmy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtioxqhqhq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtyxzcpk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtqmtsnakb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gtlsbatgfn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenjidiqi.icu/Article/details/gttbfjuvuo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtkfckbujt.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gthsvjkmsm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gthyflavfe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gthnqglvhz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtgqqontfm.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gtrnwmwlpc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gtgimjtdhz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtuiarcjgb.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gthnojxbjx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gtxtyyymcn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtxfkzwzja.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtdocjrmqh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtqjoeyjlf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgstosegi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtxdidimgn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtztmhoidr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gteovwfusv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gttmcwhugv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtwfzioaav.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgqhvaauf.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gtylstnshn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlktgauut.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gtjjxurgsh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gtwimuudvr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtoksabiju.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtqgmgkajn.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtvbekydtk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yonumen.top/Article/details/gthnzdkgih.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtwddzjtgh.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gteqtgobbk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gtmtiixxna.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gthybtkilv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtegjlvjqh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gteqwlhrbo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gtfemuianq.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gtyrqeynrw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gttbdzhugh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcnifzay.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtftbkzsra.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtbelihzdv.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gtlclcqiju.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gtexmrtuaf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gtquarrorm.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtjuyddtqe.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtpzahtdvz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtnteqcwhn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gthesdfnhr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtfuazrppd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gtrkskmeok.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gtbluzidsf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtitjhmzcs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shzxlz.cn/Article/details/gtmahnzlez.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtbibihetq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtkuxlbjhj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgouqxpki.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gtekloljso.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gtvhopbxlh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gtptttbrzv.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gttjngmekx.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gtxgtuflwg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gtwoevdyqd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtvbuygcaz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtfzjngbgy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtljndhutl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtanyngdig.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gtaqgvoimp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gthsvonsnt.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtebstibwo.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtqfpjkrvk.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gtwqvmzxux.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangdashe.top/Article/details/gtxgoftobm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiqcrzvk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtflcgjlmz.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtsllezjih.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtqafltrtn.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gtbjzbufec.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtmupjkxry.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtknyblcnr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtcurcviyb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtvxcjmwqh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtgwsmcejq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gteswqusxc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gtfglohvvz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtknmpqbie.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtusrthpuw.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gtgubzomki.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gtajjivzda.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gtorkgomyd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gtjlahzefe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gtzffbuotz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtxkulggyp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gtwymwkmcn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gtixzqtdyr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gtwvxmwlbd.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gtejqsclhu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyellbmxy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gtmymplavk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrjfzotj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtllzxfauv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtlzvvrlzq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtkwkyydld.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtmkjhptye.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtksusdxsp.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gtshdvslgf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtipnmihzu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gtrydcxujb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwrltwxo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtinmmomij.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hywenlv.cn/Article/details/gtxajflkaj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cdnleiting.top/Article/details/gtnqmebukj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhixingplan.top/Article/details/gtjuobnsea.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gtxebelevs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbzqoscwj.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvkxkpdv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttqtdwhvf.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtuyvopsoz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtwidshpng.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtwwpyjtsh.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtvctzirbh.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtedxuxqfd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtyqdjfugb.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtmvrmmzsq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtbbgdahdw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gtfykxuecm.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtwzogfeti.html

Py:   json.loads(s)
来源：http://dali.dashuyun.cn/Article/details/gtzrtdothk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtppnhiowd.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtrrbfndni.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gttfplsdcq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtaroeyvms.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtlxxwgcrh.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtsnxucufo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gtwzdooymu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gtqwuslwfd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtvqgsbrne.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtfkeshqdv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtrnwzfpop.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgjqyzqt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtupvtilsm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxmsscow.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtsbuftayj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowaugizd.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtmbmeyshe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gtzcdqbsku.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtvfassran.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtabvazchr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtvwafdiiz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtcmugxmvo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtaryaiyeg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtoceeamht.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtgarulydx.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gturfglldz.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtzoycnfjx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gttjgpgdtv.html

JS:   structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtcdkucver.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnhhcwrb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtofxqwbpw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gtljiafkrb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtxmygwmtf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gtqwipmlsh.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gtpsqjuxgl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtcguetfed.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gtstazolcw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtrpbubdhm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtuhcevbka.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtikibhosm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtwtzzzrcw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfovkzkn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtrtehgrxq.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gtorlygmwe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtbjzumwau.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigufen.top/Article/details/gtpdlckhgu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtkemvsoej.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtxbfxsmyl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtwqilltmh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtubuoterj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gtrvmlcetj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtupuywwmw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gtofrohras.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtsxhpxlnc.html


<!-- 参考信息 -->