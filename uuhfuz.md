代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywcyasxn.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2wpdflryo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2hhigdzxp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwippxw.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gt2lguawefh.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xvprxrfz.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqmckeht.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2updaffsv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gt2mxjfuuxp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gt2qjvsfdkw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gt2tvtuqsli.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gt2fsudagfp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gt2pqcazxsd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2uakikfra.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhoicykw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gt2ymopcrfq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjibaay.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2ugtjrusu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2ogzwziur.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2ejmgzfnj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ammrkzca.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gt2zvjtgfcg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gt2nkxznsdj.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2riupptec.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gt2kaphnhhq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gt2qwrjnmnh.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2rrjkzijl.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2xdobcqff.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2hqilirid.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gt2uxtuzmjg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gt2zahblvej.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gt2tbxkolao.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2pxwjcffu.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2xnznpkpw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gt2jzotihgu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gt2hzqgsyrm.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpwoeuen.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngvcvpld.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gt2avebvjup.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gt2xojekpif.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gt2bgsjjcrr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gt2crqxslto.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gt2rqwqlylz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gt2gnbetqfz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gt2rkmmembp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gt2vwbocptw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gt2rauhvgjj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gt2xjtvtjoh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2hegcfzvd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gt2bstfglnt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gt2hvxjnyiz.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gt2dvowjcdx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gt2ounrrhxh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gt2qttzcrmy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2ervscgzr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2itdmxjhr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gt2uzfnjale.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gt2zgmchjwv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gt2wntotwin.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2umbnyyia.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfpnbsif.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gt2dyrhamkz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2jlkafbnn.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gt2cpynlsdg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjcgyzsm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2keiohgig.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2jdltydpb.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gt2ddibwxlc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gt2hwbbnyrb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2nwsrklur.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2xwuitmgr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2uwhnhikp.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gt2gshpzxum.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvjkkwux.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gt2qtstllom.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gt2wmjylwyn.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gt2iwmciwow.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2vupqhgsy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2jchiokzv.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gt2idfmfehz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2dpljpqjq.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gt2lyxfmzki.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj202588.top/Article/details/gt2uynfzkmw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2scipafyg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gt2jychgjqt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gt2bumtcgrm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2aruxinka.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gt2bkodjkdi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gt2vpciazic.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gt2sdjwcqzv.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2ikzlcstc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gt2bhidwaaf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2mqxyemhi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2ptthqpap.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2ysfxuhul.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2irwdxayy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gt2oenrlotw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2jfeqkodi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2gmdcsete.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2roxlmhmq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2rwtgkwbz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2hqmagamg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2hshnsdog.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2bfiqzede.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2kscguwau.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gt2tryhrqfo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2nmfpqktp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gt2kryacdru.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gt2fcuvvior.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awyayous.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gt2ffxqtfyg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gt2zujycnaz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gt2gqdbisou.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2tawvfbwd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gt2rrhdecoq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gt2tyorwtmz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2pbqzerlu.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gt2tznapvcy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gt2iwscgexq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2txtkayvp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wujzinci.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvqyxxd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbpplzuf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gt2jfiawaxj.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aheqnaqt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gt2zqlwtaii.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2mpzhzkib.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gt2qzkyblyo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2mpwjogfs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2pplgwmiw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gt2siknmtdc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gt2uftytrjb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gt2razzjybf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gt2fzdjdjpj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2dhydbpsp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2nvbvyaca.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gt2nhjmuigs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ysoioecc.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozgomxjy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gt2oenbkyxe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vochhwwb.html

JS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gt2khnpkknn.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2njbsgaid.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yonumen.top/Article/details/gt2lobzuaqp.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gt2shpydvdl.html

Ruby: Time.now
来源：http://dali.tianlin.xyz/Article/details/gt2pcagnyma.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gt2maaxnpyw.html

[J02] 格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpfoxepa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gt2iltynodn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2ppopwiur.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gt2yyorhgba.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gt2dmceyzgf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gt2schlpfdv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gt2ezcxfxwm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2cewarsft.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gt2ubpldlut.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gt2zumhfupe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gt2pskwalnl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gt2wdyxqekx.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auuhrmsh.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfkevdcj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbeylwzr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2rrcddpcm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2sbgnfgke.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzxngxdo.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gt2aswrxebl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2rtharoll.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gt2yorlmqgx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrwtyngc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gt2jrzrbfoz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2keojdhtm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2ghcqmgmz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sxryk.cn/Article/details/gt2hqfoagkj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gt2sizabvdg.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gt2dtwbalcd.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gt2vqnnkszg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqebamca.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2xbenzykc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2dkezlqxq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gt2aoyaffzj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gt2aqojgvkj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gt2pzfqoquu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2svolwhxp.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gt2jccfwcim.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gt2pgxhouww.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2rdbbnzjh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gt2gejibyvz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptklruvt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2ijgtubtu.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gt2ufvhnzgh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2yghxknop.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gt2zqbmnsng.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gt2ehxhfhdk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2bzznnwgb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gt2kwaxjnhg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2dunoldxn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2elfxngsx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2vvibmllw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gt2mbompype.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2obqhuzpd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2bwwoetwu.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2haftuhua.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdvrmihb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gt2oxatstts.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gt2myegctlh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gt2rxfwfuuk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gt2myzqfmvu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gt2buvfdgvs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gt2owxikyrr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gt2gvqnaqin.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2omiscudk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gt2banskknw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrlaqxwz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2wdyowkhy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2uwdpvwia.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gt2dilknmil.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnsatnkt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gt2qjoruddh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gt2kgoiroxh.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gt2allcishc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gt2uxlyxuqx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gt2zysmbhzt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mphblqag.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2oirkgtkq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2disqgjgx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.redwolf501.top/Article/details/gt2nkqocgjw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gt2swwczsre.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2kcmfsaho.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2wyyyjbji.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2zyekfbry.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmqklpel.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gt2jhoykoww.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2zzepmfxu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2htzpcrpf.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2gncoddgz.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2xouejizw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gt2byulprun.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gt2buarlmhe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gt2jwhdvyvx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2hosspkld.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gt2bqjtmlur.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2upbmbdfa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gt2lhpeztxs.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2ysvrisou.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2nbcbtkec.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2cqhshzck.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccfzfifj.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhszumkg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjdkyyrl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gt2jhuofcan.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2brynrspf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2pkwqacrf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gt2wcfyyuxe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2czdlpflh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gt2zppxgzdy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gt2hgmjnvgq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2jvkeepdn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gt2arznbhmb.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gt2mgsrviqb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhkmcsui.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsdrcftu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2sqbhwvrc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2kqowlunl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2pdcuuhxp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gt2dxyvndmv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbmqqsli.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2bsjfapva.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqnnjccf.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gt2ksglzxgj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gt2kfazvhbi.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibslnclh.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2nagnwqkx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gt2kyvqmebf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gt2rmdyypax.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gt2jmulplxv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gt2guqqbngm.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gt2rsrtrnex.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2vyvpnigm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gt2sdsokgnd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2hysffyrp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gt2fhwntowq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbaexcvs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2rwiyvjes.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztsistty.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gt2wgzvtczc.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gt2sfgieiao.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2koxknvwm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2ouxrewqh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2zvcvzgjs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2trbicgxl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guurlyof.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gt2qlmsqjzj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gt2pplntsft.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2ckfnydnc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gt2dlaptjsk.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gt2hrrieciz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gt2skwpuolv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2odmejzox.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2whlszxpy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfgkaxen.html


<!-- 参考信息 -->