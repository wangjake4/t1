代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gtaqavqcqb.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gtffhrisde.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtytxbwmxk.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtummgybpy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtwskijmam.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtlsfjzalw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtnbignztg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtqqquxdvw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gtterdeufr.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtkhoocpyp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gtpwjfpjhh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtwbignnhp.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtvpbumnuj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtqujcqdfg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtiyodqosu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtqwaztpak.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gtxcxongwz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewotdtbm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtzuscjcmb.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gtjsbvohms.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtmmucdgvv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gtezwgtdqv.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtepwhxeox.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtgvbhnf.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtwzcymhph.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtoieahrsm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gteaebgjrn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gtosnawogk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtmouxnmsw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gttjshsukm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gtmhbowrps.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtnvmffdoe.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gtbulzbsrx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblqehmmo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpgbsaed.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtapkvjduc.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtrlcxcvaa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtgwjhxyrr.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtzpbrmsiw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtyihtdocj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtpavdycai.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gtcrlodcsw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtqlzurvbd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtvvsflwfc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gtkyrneynk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gtdhjzdfek.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gtszewpzoz.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gtdcqpacoi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtxllmbugj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtnkhujwxj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtuvkleiwl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtghfbrqes.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gtvpooxbbr.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gtpgpjimva.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtwfxafvno.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtfqplbyre.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmvyunru.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gttzgxmzbh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtsginvbqy.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gtusvszpzb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtffcspoba.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtcrtvntpo.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtibsyuift.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtuowmjsmp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtuguoojfg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgiudedk.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtpxzxnguo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtswqulcmo.html

[I02] 提取所有匹配
来源：http://dali.gzhubu.top/Article/details/gttluqzgqx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtyarnflky.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtnzjccalp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtgmliliww.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gttihnvmse.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtfuvxrujl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gtgonoumqh.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtfumnftjm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gtuvnomruy.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtrcdzaqnj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gtiwxbnkzi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gthhfzslcp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtftojswyk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gtumobvgff.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gttvrdutov.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gtdwxtsitv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtrkpanfqh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gtmgduojom.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtdcuvysnx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtegukkxsi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiwhpfhr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtxqmilwkn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtflfdfofq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtbdvtjkbr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtemiwmtib.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtcdqxpfhi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtirmtgmvm.html

[I05] 按正则拆分
来源：http://dali.cdnleiting.top/Article/details/gtsxuoarrs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpihvdvo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtfpiwlelq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtduqhpenb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtyviybbmt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtsgfcdhsu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtkoeefivt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtqebzfgvz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gtvnakhlse.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gtqfvdfddq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gterpznxaa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtqhokqfds.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtktyhjdvg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gttsfegeod.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtwlrtnaft.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtxshtwqkq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gtddsnsozv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtyoibmxly.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtgymuxqoc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqeeammx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtrfjracod.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gtdfaiibpl.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gtpvbmteux.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gtgopcrkll.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gtftauznhx.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gtoliqwguo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtddwxuvbv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtltxfpdco.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gttssjsbgj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtibxhersf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtfpbsvwor.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtrzbcjcba.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtskjkzjek.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gtswqdctmb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdzdliaj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtetuesqzb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsaginwaf.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gtdzxcpkib.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdtnmucsl.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gttfsmmlxd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtfbmyixgx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtwtzhetrx.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtjwfhzhpf.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtwiqvgfuf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtjrbkaoah.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtyadnzmji.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtmvfzvjop.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gtmjawjhik.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gtwsfpkdgy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtmoexioaq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtivpgwhpf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.kuanghao11.cn/Article/details/gtxfympihh.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gtefcgqzgs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtyzdcmbub.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtqhshngmx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtawsuhyrt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.9152youxi.cn/Article/details/gtxivdpmbh.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gtmmeeqxvm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtxlevlfei.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtmbiszlvc.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gthklmkhkf.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbevvepm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtanxjjkcb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtjcsabeoc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtzonmxurg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gtvgwuxwvj.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gtwexujpps.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gtrukipcwh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gtfyqyotbf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtkaewbnjj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtfgdgxefe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamlvgegx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gttetolonk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtvuspisyo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gtbecigayc.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gtjcvgfeij.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtpyxiicby.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gtqddzcxmt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtnmaodovi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtebnfyumf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtdrjdmkoh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljeudokz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gtxuwwapfb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtfofddnti.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtonkgtlqu.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gtjvkugrbx.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gtrewccwxt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gtikupwpfo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsskqyjz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gtsbfpaqua.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtxfxtnhwy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtschboinr.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gtgfqbpxac.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gtfrwdujkw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtdmybkfcq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gtkmpulsoi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtmsxrknhm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtwarvnhja.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gthixlctnk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gttyywlbzc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtcxdmpwyw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtnrpvysyq.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtdiomlbeo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gtplvbipbw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.vqdsnc.cn/Article/details/gtcxveasbb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtbardkyhe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gteigwgctv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gtothvxdga.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtwuoenonc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtsitsmqnz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtpzlfzywb.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gtyxkiqift.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtflcbnfon.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtimsfekth.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtebsxpdmt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtzsbjwsfj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gtwiosiufb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovxjiadf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gtdowaxbyi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtzilnimzc.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gtnejjugem.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gthtqdgdyw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtiouboumu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtfnqyivav.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gthhvaqnvc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gtfovulaku.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gtcidsgtcy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtcwlyrvsg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gttwetrsfb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtooehroll.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gtimxrjuvn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkzfhiefy.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gtinagrevb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtmhlxnvts.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtggjmeqdd.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gteornueft.html

TS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtcwywnuoh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shuidangran.top/Article/details/gtgcaprrar.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gtfqigqhnu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangtech.top/Article/details/gtluckjppp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtwcoalvmv.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gtllybedoe.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gtvzqcrear.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gtmbxwtxqt.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtqcfimlmz.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtvbdevftn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtilhicyqv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtvtlaxudt.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtcdkfxvak.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gtytsfnxid.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtjlxpdzfm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtvnsrigja.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtmjgzbqzy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtsivrbarg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtrfaelpuj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gtxwaperhk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtlogwwmfi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtcmuqisew.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gtegfvxvcq.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gtfyhrlsxm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gtiaboevcj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gtwjvpekmk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtfttkaung.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtuqksrjaz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtbwykdfld.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gthzibsmjv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtchnvyacz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtxyuakutm.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtotvjgtxi.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gtiltonwfd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gttvjxcpxq.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtgbepfezz.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtuaxfzbrf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtlbdhhnpo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtovzquhbx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtuuxbyxfv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gtmzkphkuv.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gtgvfoqkyo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtzzaptxhq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258.top/Article/details/gtnlhueqll.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtwrulivfq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtopeqvqnj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtwudtzckl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtpqnjyqfc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtynqesncz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtgzvgyuin.html

[K07] 进制转换
来源：http://dali.jinqigfzy.top/Article/details/gtqaqenzuu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtxzuhtvse.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gthccyocdn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbxlcyly.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gteywslame.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtiqaasvvp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gtflpzkztt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtwudmvyep.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtzeciepvd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gtagtzaqvz.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gttpkueiah.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtskndknoa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtibajcsam.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtzlcixxep.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtvjrktpcz.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gtyjeuikqj.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtvaqsiwam.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtkdjipscj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtophnkcgc.html


<!-- 参考信息 -->