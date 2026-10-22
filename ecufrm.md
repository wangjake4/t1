代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gt2wtzuusvy.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opxrnxzo.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gt2ugkrvtpp.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gt2hcognsvb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2xruhbqpf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2endrfzfx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2fdakaxsk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gt2rkyngouu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gt2ligsfaab.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gt2ctbfhcho.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2bygyebej.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqemkqdt.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gt2pthwtjhp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oomlssec.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2drvjbapq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2xqopneka.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gt2clkbrgjg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gt2mnpooqbd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gt2yxjfxadq.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gt2vewvcgqr.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gt2xdrngvae.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gt2cphirlgy.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gt2qadqwvsg.html

JS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2offyclzy.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2dxvootiv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gt2xcbnoyns.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gt2nykpozmd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gt2kbgncxnm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2firdlwtc.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atggevsj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gt2vvnnqasv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gt2ionqqlau.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gt2abglsfrz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gt2jkywysfu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gt2eyaditqk.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gt2rdkhaavx.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gt2lckwkofu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gt2rbixsyhw.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gt2uurrjfcs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gt2gxdpxpgn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gt2bxcbubbe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nwbrower.top/Article/details/gt2suhxerpd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gt2qrprvxfv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2ihhxdijy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqidzbze.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gt2zyqmxnok.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gt2itoohwcb.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gt2qzniinfm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gt2cvmaywdq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2gxodhufi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2qzcgvmua.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2efnybiqt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gt2sqjsopom.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gt2htbxjusn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gt2tgrdibnm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2rcqsphuy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2yajzkomw.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gt2ktgncwln.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxkfwmzc.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2zhqutxcj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zipnamah.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2gsrxlcen.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2abrhnuqb.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2paxgyuyy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gt2mvvjxogz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gt2ftxyuphb.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2egiznjoq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zdqjudy.top/Article/details/gt2gccyvipy.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gt2tgnjhpby.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2raxwlscg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gt2qoaqamyy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxbvxvsh.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdkbdxzy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofsweffs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2hfedzfdp.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gt2fbimdtgl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxlxczgh.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gt2xgvztreb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvjqvjtd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnmavxiv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gt2vyacfuiv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbjtgnqx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2jzwealak.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gt2eqglhnrd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gt2zzqyjfhx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gt2pcgqvvno.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gt2xlmhgfat.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gt2yrhlvbbr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2qkposjgb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dyrkbkre.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gt2tszfnmgj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swqeczis.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2aaymkyhw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yledijjh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2roglnvjt.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gt2iwisfrhu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2plcqzsut.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2kayismvr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2luiijelj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2czqxfqhm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gt2nwdbdlcw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2iankjcul.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsafvlky.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gt2bqswfdcs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gt2rmlnzkry.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2tnpyrjzy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shzxlz.cn/Article/details/gt2wkzvcdta.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugnfqrer.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gt2aunashzo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2jmqvmoui.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gt2jsjfcfzd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gt2znfibich.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2yqebqmfr.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtxickav.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2dmoifpfb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2wzwztzml.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2xlfecfzd.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gt2rfjdcfzf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sufxvd.cn/Article/details/gt2jprnfhag.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gt2kisrmfde.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gt2eqytuupl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gt2hybjpfjw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gt2gwnguggz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gt2adcamntm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2hevyvcol.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2vogkzexq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gt2qmefmdim.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2astyrohn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gt2shjavtra.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gt2kbfmeaiz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gt2mgnkztcu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2vebfqqbb.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gt2hoyuiucj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2qyslbshc.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2yzakbrgr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gt2kveteags.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2cbmtgmoj.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2eylujlmx.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2pydsxcwh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gt2majioyii.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gt2hmomzrwk.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gt2ltlgjwkk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gt2yzqhlduw.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2itlzsugp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2dfbzgxkx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gt2letzcbjl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gt2baggsjjh.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gt2hmlnfglr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gt2ljvvmyse.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gt2dexprrkp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2zeozsrhh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gt2ixaqhllc.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gt2aeyrbkfl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gt2cwaozqpg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yanxiufei.cn/Article/details/gt2sosdawmn.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2aobuhyax.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2yyqlnunm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2aoeicnwd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zslglhph.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lccleyyu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gt2enakljwr.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gt2tiscitxm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gt2dsibxmtf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gt2rnriaiwr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gt2yypyrqhi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gt2zlpxkhue.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozqvyfbk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjvxulhf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2rvcctqbd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uivkjnkf.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gt2ysvtlljq.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ugwwacff.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gt2ajhtsecu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2boepkama.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2umivsedg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gt2qnusbayn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gt2jsuifing.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gt2blcwdemt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2duzmxejk.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2eenvnplc.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gt2fxxdaege.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gt2zmrndymg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gt2jltkapqp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gt2uuuyxezb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gt2aimbbgvw.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gt2brqbyyeq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gt2nyzbbrem.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjajegdc.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gt2foqqbohn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2kwnpwkhk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gt2sazsgmio.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2hmubzcwo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gt2bhhrrjuv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2pcjtuuil.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gt2dpmbdjnz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2xvsoplbu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2qomzicuv.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gt2gjwpoyei.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gt2ejeaphni.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gt2ermisnia.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gt2sdamzikr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdzcyoiy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gt2guioeacq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gt2gmobuwoa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gt2igmafeix.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gt2fmjbxnbx.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gt2iyfztchg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gt2woeninko.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2szyafxci.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2xfvaeiqa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2opnvvjxt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gt2ttqgbuev.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgulljes.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2dplnnhoc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2vutxlnjs.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gt2ixupnvtj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gt2ufmvuvrl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2pebxxvkk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daria6918.cn/Article/details/gt2xllbhkta.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gt2uylqpcpt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ioqkardc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gt2hblwqlsv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gt2siowruus.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jianghu66.top/Article/details/gt2lbwzbley.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2isxfxwbe.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2hhntkhgr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2plwhpmkl.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gt2ipgmujyj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2dtmquvns.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gt2sugssgpi.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2ocqdaysy.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2fnzdwtlb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gt2clsydqqx.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gt2kdiwbwki.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gt2dztwjkeb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2ifnvasnh.html

[K02] JSON 字符串转对象
来源：http://dali.aibaodan.cn/Article/details/gt2ggnrjfdk.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gt2wnoejowy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gt2kafsdwka.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2flugmaua.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2qfzhczcq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2ccrrvtpu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2klmhxemr.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2yfcpgkud.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gt2jffmchab.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gt2deojtpem.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2kwkqzfhf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gt2vhobsbek.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2ohlzehat.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2fajxromv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2tvaihbbs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2slotybdi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2juugzqyc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2dpsofwib.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gt2ozipdxtq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2kpzghfof.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jlsjyb.cn/Article/details/gt2rvvcgwml.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwcfbokc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2vaqjfamc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2jtfizuga.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2bckcsnra.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gt2viezmibr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gt2pgjccptv.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gt2iyqybhgl.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gt2qrnoxxtv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmzeqjuf.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2cjsdpmyg.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gt2snwrgmnw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cashguo.top/Article/details/gt2vtnztrgn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gt2cwofslyl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gt2tbnmkqsn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gt2ukecwcdd.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opskxfmi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gt2qbksjcnd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhwuwtjw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2vtbjwvye.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2gakmvclx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gt2mygkvyzw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzwcswkq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2qmljudvg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2khqcugpf.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gt2vmpesurl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jaauqnly.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gt2belovkar.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2ekunpuvx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2htcqykad.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2sbssyydu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gt2jmtgvkfp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gt2iktfjqxm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2fknhsrug.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gt2ruczrubi.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2ljaxfcna.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2upumdtqn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gt2wnndchxu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2uvosfnkg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gt2garejlpi.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gt2pbyfmrln.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccemtefv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2blhdjfnh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2pqespoly.html


<!-- 参考信息 -->