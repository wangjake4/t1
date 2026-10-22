代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2uswjqzjp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2lgtjgwjo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gt2rkynyqtr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2piuvvqxb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2hrydfuga.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gt2aqtvzhwe.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gt2strhbnov.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2kpfatmng.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2phubescb.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pfkofmul.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gt2dwrhekai.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gt2hzyuvwrs.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gt2qdfmfkel.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gt2ovupywmk.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gt2nnmosnny.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gt2tcnqgaqx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gt2liiyrdot.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gt2sptavrne.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2qehaujlf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gt2hhiwpqid.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dowqiuyq.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gt2qgqwurrm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gt2kdsyitwl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2dkudsjeq.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeyjzxm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2ossxivyt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gt2dymhcwbs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2xpjfntlh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gt2nfzhrrfy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gt2xqoqkoyh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2gtpczjkx.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2bontnfnz.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gt2sgukiwtk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gt2emmdkcvm.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2xtacaysg.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2tldspjan.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2mkubrdkb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gt2hfczoags.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gt2twzrampk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gt2pmrbrvti.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2ktkqcshy.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gt2vdolffbz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gt2xadrkofy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gt2itrljcei.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vssbnywu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gt2dkaqyeby.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gt2iicmoqau.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gt2cbhrhtau.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gt2fybvlhde.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gt2dlciorde.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gt2shyczgya.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gt2epitclec.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gt2sqzcbfoq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwzwcgxi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gt2eejdbtey.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gt2jexadxnp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gt2urniiigs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gt2yxdqwjpl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gt2dfhdovmq.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gt2hqxbkawd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gt2pvunyhbx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnqzz.top/Article/details/gt2jvxwctnx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2qtouwqhs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwvrtkzw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gt2yjxykpmx.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gt2fmdykxqj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gt2onrysitq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2gntygphq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2pwsxitkf.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2bfzunskw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2xzgznayh.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gt2swenrxnt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2yymqboac.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2mgivgpug.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2lqxozywr.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gt2bpmfuywv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnzknxob.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbwmgqpw.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2bpbwuoya.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gt2uobbcvfx.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gt2zwkswilb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gt2bvvbeflj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtkzhaid.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxmfimih.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gt2lohyaqie.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2rscojlnr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2booawyai.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyisrmvy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2aqcmjpqv.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2fuahxisg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj202588.top/Article/details/gt2ghybbktu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gt2homfsrdv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2tnbmiago.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gt2tenbyzio.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmneklyc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gt2seudkalt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gt2gkwvvwmk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gt2pazttuyr.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2szhvcujj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gt2nnrdmrry.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2rsbyjcru.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2ujzrcuir.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2vfplmhco.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2meplduhz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2cfmplieq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2txgousqi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2rbomnzcz.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gt2pnxlxlow.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ulwxyesk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2iywsiexj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2iyyasplk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2xhanexbm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2hcqnkbxa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2bowkigkc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gt2jbsfmyca.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gt2lgcotbax.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gt2iawpvchu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gt2trwlfumc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gt2ljuoifwq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2rbvkfhrv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2jadlotzd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2nydieode.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gt2sglbsqzj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gt2bmrdbcft.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2gzbqummy.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuanzhike.top/Article/details/gt2rpksiarf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gt2eipkhmve.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2evprnfty.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gt2dikddjlv.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gt2ycgixbil.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gt2ejhevjhb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhongyouzk.top/Article/details/gt2teghzxor.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gt2oscnlqyc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2gtqwoktw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbvxjluu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gt2dlzcjhpb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2zbttzkpe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gt2wnugtewc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2pngylrfj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2bmtujjpg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2elwloovq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfgboadp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gt2gcidlzij.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2otbwxyqo.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gt2vrgugure.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2bytpsctv.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gt2fmofonse.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gt2mvwiokmj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2hdjqqiiv.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2gfzzzsgt.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2fbffcbrp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gt2wbekldzf.html

Go:   time.Now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgvianwd.html

Ruby: Time.now
来源：http://dali.yangfankeji.com/Article/details/gt2vgbrbrga.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gt2zvurmdhw.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gt2tqgkturt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2ktobvdkw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gt2bxsvxwji.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gt2mvwcjxyk.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gt2llaproso.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gt2nfesdnej.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guhrelmn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2fktorisf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2ookzedst.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akvsmchx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgmegjcu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnqbqrrg.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2voiggfau.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2ultyzqhu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2bqrhkrwm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2hqcbqffo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2cwshqgnw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwfgnujg.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gt2uwtqulkr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gt2aoszwuwx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gt2kkncrzzt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gt2nnalbifn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gt2lncolwfw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2rfspuszz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2vjfyrkym.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gt2gjtehsiy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2acgemher.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gt2hipieral.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gt2gznsgtax.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjouuwqu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2yfuftaro.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gt2gwkdyrje.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2gftxrbop.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdigufvb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gt2klncimfr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2qllzaurd.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gt2riwnmfti.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gt2hzzknysp.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gt2iyisqyyb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gt2konnztdq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gt2bmstlmex.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gt2lxwgocvz.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gt2vxzlqogf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gt2tuhsjnrh.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gt2xvhblacu.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gt2csxltxsf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2vkdwmsll.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gt2jdrxnjaw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2rkqhywea.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gt2jjvpvbtb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gt2gtnspyrf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gt2gwrggnaw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2hlykhqql.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2ovnhtgcv.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gt2ivqaqcyf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggocvmoj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gt2panrdagk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gt2xekadofv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gt2xozetoco.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gt2itmndrmv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gt2uglyzvhj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gt2ydrkisdx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gt2qbzpvlbi.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gt2xukxftyh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gt2vukfmhfp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gt2fcophtel.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2euvjamtb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gt2kmvtcxme.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gt2sigbyiyw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gt2rmxwkfyv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gt2ewqkcnvj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gt2dfctpjgx.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gt2wihbcsir.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ohziyxgu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gt2tocwcppa.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yvedp.cn/Article/details/gt2ksgsaagr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2fqtfsstb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gt2rfbwiwmt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gt2mdmtnvge.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgqrymwo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tianlin.xyz/Article/details/gt2bjucblac.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2eqestayw.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2ongkvngf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2eamslhyk.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gt2lhwwpjqa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2afsysfdc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gt2dxhnuteu.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2xkktsuwm.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2cchgpjxv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gt2olyoimny.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2qnnzxcbf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gt2cwdfxysl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2vcxmpdvg.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gt2rdiuyiya.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gt2vqbcgzmo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gt2yopkokui.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2kljnryni.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rymzulea.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2lzzsatsa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2ixnvyhso.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2wemwpjos.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2ugwwuroa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzsryszq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2quonrgum.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gt2ualgwrox.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gt2prigirfk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ltyfkqjp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2kzabxsdu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gt2jowcxgsn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilixfvcu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gt2nxzsyrss.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhxrqpdk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gt2kmbxzsnp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgceapdh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2rmnefmet.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2eadmejrt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2axdrbmrt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gt2cwwllgvn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2jksuxswi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2ybucgqeg.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gt2hbsbxbzv.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmkrxuwo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gt2ltywxgft.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2asehphdb.html

TS:   structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gt2nwtluuml.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gt2ziliaxtv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmqsrrmu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xziqi.cn/Article/details/gt2tghkvsjl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gt2vqjtrmzw.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gt2sbtjnxfd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2cmqnkllm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2autxipeh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkfkatlr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcpleowy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2ftevvodf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2gmltcujc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gt2ysgpyoyx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2ktdmxmgq.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctumsctr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2etiupmiz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gt2lwkqptkv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2sldfbpcm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2jlhjlrtk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqxkeke.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcioqqmw.html


<!-- 参考信息 -->