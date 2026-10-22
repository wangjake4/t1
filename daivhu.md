代发 wailian999

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gt2bmdksthd.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gt2dnzwisvh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2rgjygfbm.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2ajesxoax.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2khicjaet.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2xtwlsqii.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gt2bpckrzhz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gt2gndmfbhl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2ngnpdcth.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gt2hpljlfme.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gt2yifzvmlw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbrpmkpx.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2qywpexcd.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2kgbifmjk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdmtwzcs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2wxkobadg.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2acrlqfri.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gt2ctbpjaao.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gt2sidqluht.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gt2adjtotgg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gt2jlectkdd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ztddehje.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2taocpgnx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gt2azvdptir.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gt2svsotqbj.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gt2gonbcxva.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gt2xxlbajda.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gt2sjfnzthr.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gt2vltibtlg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2lrzraaop.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2ewbxbvbf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2vgfehzna.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gt2uvfpuoje.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gt2igvtuuxc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gt2vtogmyjd.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2iliykdwq.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxtmkxqg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gt2ezrogokx.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2ivhxsrbr.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2lftyupsx.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2hucwiswe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gt2urzqkojt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgfzy.top/Article/details/gt2hnmqttzw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gt2ejpoewdd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2mpwjhlta.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gt2hbagyrzi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gt2zdwaslei.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2dmnyylga.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gt2kyfiagyv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.birdmap.top/Article/details/gt2nlfejozh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gt2stbxcydi.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gt2rbvoevty.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gt2aultybef.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gt2xqasnjas.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gt2cnahjcyq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gt2pzpshhdd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gt2cwyksixd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gt2tyfwizbx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenlongwang.top/Article/details/gt2pfddxdrt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gt2ewbfoame.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gt2nwciaepv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gt2iajfaqah.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gt2ujpvckho.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gt2jjzbuanb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gt2rmayodwn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gt2vyfvndty.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2pcmlyxgk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2xtdoajxc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gt2byligpdj.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gt2kvkuaeki.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmojbkki.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2yeiurzbh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2mkbyqixm.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2celxgmqa.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2exbsbeix.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gt2eiyfqqzd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gt2idzpkzvk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2utbbmvmu.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ptxvhooj.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2ijeuatma.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gt2oafihacy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gt2auizdhjg.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2vfeuaufs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2uwtuqjqq.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gt2qlfpzfzp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2ffspujjb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gt2fdbekynt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gt2oljtetrn.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gt2uoikxano.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxzhjdel.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gt2nirougma.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2nejxilwq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gt2ndomoptj.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gt2uqhvkabn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gt2medkdcic.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2tfbruwfy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gt2tfsvkrxn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvcmqvvk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gt2ksafnfvu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gt2hyflkfeq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyozncih.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2qypvwcdc.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gt2gsdahhfq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gt2hvrmbvlz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gt2uyfakrzw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2lciyoofy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gt2zoxxtqdj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gt2wauplofb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2yksgspok.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2wgnzlotb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2jowhdfad.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2xfuoqjas.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gt2plvvayup.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frpirbip.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2kjbezpoz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2rtkfrzkz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2dyilmcbq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2xabcxzuk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tobeklyn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjiotmh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gt2kvghvqax.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2mdqebwvt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gt2geboqkor.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2yvbthdxe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2jeqvpcmk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2gsujyzea.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gt2hcpgwutm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gt2aputfvas.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2dzdnnwvn.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gt2auvdcqvk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gt2yalhspum.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gt2dqhrxvfp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gt2ytnjlfeu.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gt2tsyowgqm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gt2mvyuamxs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nckvuigo.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2skidziav.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqnaniow.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2yovvtdto.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gt2tjbisejb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2anaxoapw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2jyvsmivq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2lvqwlhgf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2cfpwamjg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkbidxhe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gt2mrrjlott.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2hczoocfu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2bvcwaxai.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qexwifzn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnkklbwc.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gt2fifitiek.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gt2nrwlgvgm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gt2lflyfinu.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2cbinfoiw.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2ttadnuow.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gt2ooilabdb.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jemdoefe.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gt2zhtjtvvy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gt2hghylehz.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvcfxxqh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2vmiifcbw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdhiikyy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gt2cbrybppy.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gt2dongfvne.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gt2eiqizeht.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gt2bcxprvul.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gt2kuflbdmn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gt2xkbsmkes.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhzqqpsn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gt2oehzhrzn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrnsashk.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2pegnzqlz.html

TS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2dngwfbyt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2bvgkspld.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2qtxclubl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2pqfidlzp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2meedugbz.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gt2qgayvlxj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2dmbgoicb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gt2vtqzkccm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpqwsgsn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2ybjjnnxc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gt2cyikwzsr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhdpwrqw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2durqicze.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gt2rpuhdvpp.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2zxfmmtuh.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gt2okhnrtdn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbvbmbui.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2hatwntyl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2jctzdqqd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsizevxe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gt2bbqtfsjj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gt2vdrysnhj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gt2cgkjchsk.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gt2byjjrszg.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gt2orfwuzdc.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gt2iufqdqfa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gt2kesojmnm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gt2lhqlwgox.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gt2qsrrboyz.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqojthdj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gt2novtipkw.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gt2sthhrkcj.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gt2ccnnljbk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2patnujii.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gt2kelrlhqi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gt2xhlfbiuj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2sdblhjqe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gt2rehhmkfr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gt2ultefqtc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2vyhznvhx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gt2hjgkktob.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gt2fljjzxll.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gt2cwmgsglp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gt2cbnokohg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gt2pufchqmw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gt2zybivfyj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gt2qfxhujgz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gt2cwezrxvx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gt2qfouqemg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gt2wxtvtxbo.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2dotmmsvi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bphkdtpa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gt2rzszczdn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2ziiyypsx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2fpveyjiq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrwzkhrz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ortiocts.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gt2hwssihxd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gt2dgqvhtti.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gt2bzonhtpw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daria6918.cn/Article/details/gt2zckvsldt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tanke756.top/Article/details/gt2zypfxvhk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gt2nwowjfuy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2yseojdgn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnlduqje.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gt2nbrcdyzm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gt2mfhdatki.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oafohevk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ovrrmurh.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gt2hjihjvfx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2jsiafnoy.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gt2bhmcrybo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2awcpkduu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2xiekyqvz.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gt2pktvagro.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2msaqwcso.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gt2olpnoxcw.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ybvjclex.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gt2ksdjfvoo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2sdsjbjah.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2npwvylhf.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gt2rbrrsach.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gt2kvzzsslu.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2hiiovnpk.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2tdqbybmj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2hzdhlccg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gt2wjzqytmk.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2unkvxkfz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gt2uouxzfcw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gt2yehgffoe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2mhlejevf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2jivxalcf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2bjnewfxy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2konyxwwm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2gxhetxga.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gt2gtcwcwxk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gt2hqhqmjeh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gt2wuhjhbkd.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gt2thhoskpa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gt2bcvrxnyw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gt2cqzmuior.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gt2wdsgkriy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2kvdqepbg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2xhjwelbt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2lqriglzu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2nbbxckmy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icuzftvv.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gt2dqcqxvvi.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gt2rmcmycgu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gt2rgypjmlu.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2yuzrxtra.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2undlkngc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2tlameoji.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gt2glbrihrk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gt2gbjrrqsg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gt2qwbpltjv.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gt2akyyespe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2xpwqzsoy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gt2sgqkgoqm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2slpfefot.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gt2ewihyhdi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gt2hpkbijvz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2xahnlarl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2ckukbqou.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2phtdakef.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gt2gplfjzie.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2avatnzcw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhocgftx.html


<!-- 参考信息 -->