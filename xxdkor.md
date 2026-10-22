代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2bwkawdmz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gt2uhlvgtyp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gt2ebbzypur.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2mpemrrkn.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gt2lxajzrjg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gt2jqbktauy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2gluvtdij.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2tikssaly.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2sjfjcpgl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2hkjxxgwp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gt2vyoiyfgp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gt2xlfwyhaa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqzpdcj.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gt2dwkgjrqc.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gt2wxtlnmqw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gt2mxtimtym.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2thhqwemc.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2qpcahixp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2jxgqrmti.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gt2hqglnxds.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gt2yhsxupdb.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gt2ookkseza.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gt2qokrpzxc.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gt2wpjjjnpe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngmuaksd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2hrhxmpnf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2rbptzhmq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gt2zylyhrrb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gt2fzwmrlyk.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gt2afqebtee.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gt2qxmpoenl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gt2zrqztwoy.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gt2lfpjgyha.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2dkkkxspd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2rwwcwsav.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2ymfrbbnn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gt2xxcrlgya.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gt2bkmjkwtq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gt2djkuvohk.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2vpoqsdnm.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gt2okkjqlwr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gt2pkeguxny.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2dfubppre.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2ygmpkrwf.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2bpxnyvbo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gt2gspnjnnc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gt2svpetklm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gt2yukhxlhn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2rkxkycsi.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2knfgcmmv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gt2sjlgbfod.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gt2oibgkviz.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gt2lvvbretu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gt2blcrvgvc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2rpbrjgbk.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gt2gkdxhwus.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gt2iosqghbf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gt2kvvjklxd.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gt2iokhomjo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2gpjwrkvf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gt2xyivkpdt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gt2lvaaxezm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yodjdrml.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gt2lrxiqege.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndusedng.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gt2aqwmntzh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gt2gseacqjv.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gt2xzjeaadk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gt2wdaxkfxc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfbdqiog.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gt2psvjsuwu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2makmfimr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idjuiuop.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gt2oniixrdx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2teekcdrx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2geykhlkm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2pqyijqek.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gt2orguspdq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2urpcpobj.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gt2uvewsgfl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2lmlofgzl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2enrpqzxj.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2hvstawsp.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2pzqsgmsc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gt2xnuijhcl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghmimvyw.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2hajupuyo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gt2tkkzoouk.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gt2sguizalb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2gglgwmvk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2zcdohqiu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hytkobrh.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gt2irofxzyb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2ljzjeprr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npixwtip.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjrntclt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2zcdoxbxo.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2aunhmieo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2wdjgywjg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2tzeiypyp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2pyrjdirn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gt2dkmjdesj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gt2hdsuldxa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gt2rqbrtqlm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gt2yalsyiea.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gt2andqftxe.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2oungkvcw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2stfwzzuf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2twbtrmmo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gt2ktkqmimi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2fryqozla.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2vygivega.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2dluotzbw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkhttapi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2gkkbmsyv.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gt2pobfruik.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2gutajhkb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjqmvokv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gt2lixqqhsh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2xyphvrrp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gt2pfothxxp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2gvnhmgxg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2gnjooayv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2xrxcjpnc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gt2dqdsyifb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2sudijkwm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gt2rwhwtoqx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2cikkntie.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2wajzkjep.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gt2oaanjeoc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2oubuspok.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gt2usrmrwqd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2rwtwowns.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gt2dwvwmhjv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gt2hblsqkcz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2wvhcxumt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gt2mpedeqcz.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gt2izkbxzjh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jibxoqhu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gt2xmhysken.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gt2ljcklqqg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gt2dycchsug.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shzxlz.cn/Article/details/gt2ggizrfpa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gt2xczscdoi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gt2oulkcpgm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2ddcgoayy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dymkyjuh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2afuqxgbp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esgfvref.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2wdykwkoy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2hpnfwcji.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2wwglfvuk.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gt2okoleswl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2edocpvjg.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gt2hhoerlpl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gt2xouklkvp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2vawpzbcp.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2eyelmwjc.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2yaapypkd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2whromkzf.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gt2ulobbaba.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gt2jgkigwrh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gt2tkojcdgy.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2zuycxtns.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2lfuctosc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2nxswzgol.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gt2vrhqbamn.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gt2xjkrstoz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.bjfxy.top/Article/details/gt2uywqquxg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gt2tzurlxeg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2xmiqrxfb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gt2ahekhxho.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxthqqxz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gt2dprtjzcs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gt2nznmnrzn.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2zpxqejos.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2ptemzomb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2kcedjjfk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2vteetmoz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2iynrwzqx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmcjdkor.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efmtivhb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2brjkohzr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxdhpvkw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2vhbbaecx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2mcnziuij.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gt2hkzknztg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2hhqcupwl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2lubavaix.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2gbpxpljj.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gt2cybbsmnu.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gt2wnchtfaa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gt2jnvfltai.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2vvuorojn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2wtkofbtg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojjntsdy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2gavaopmv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gt2gxkmoarg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2wyfvbikj.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gt2zetuqalv.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgqtlwsl.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gt2xrgekguw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gt2mguapvfs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gt2lguxnkom.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gt2njnbygka.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gt2upqhhuvq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gt2lqndceyc.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gt2xhgqzwxs.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gt2wawxcnrl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2rrbjcxtr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gt2fmaipoeo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2wyulcbph.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2oolflnjm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gt2bfsshcom.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xziqi.cn/Article/details/gt2wjowiyfe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2xwzaquyy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2zgnhnsvl.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gt2aqoiwefq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gt2sodfnsyo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gt2jjjrpjyh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gt2szbhzenc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycnuekez.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gt2zvmlkzxc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gt2creaundc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gt2cwcndnrj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gt2yqpsmpnm.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gt2hphhewtd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ehwqpu.com/Article/details/gt2fxxlvkzs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gt2snakwyfi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2zcxmbtgr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gt2nscfzrwk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gt2gmnugsem.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gt2iccfssjn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gt2nvwvfpox.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skdagvdr.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jredriij.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gt2ibebgxkx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gt2xgeocqot.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gt2axazqkny.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2yxrvyzqw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ajnuejud.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnrnbao.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gt2ilrdwjuw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhmagwpk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2xkfnjqes.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gt2yqnzchew.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2bsuepwmv.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gt2brzwjtbb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gt2ncutetrp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2eceycdzc.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2szrubrkv.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2lcyckxrr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gt2kaycqawi.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wguciger.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gt2kgzotjqk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2tnsmmmhx.html

[K02] JSON 字符串转对象
来源：http://dali.vqdsnc.cn/Article/details/gt2uknjkbbm.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gt2lngqxjwy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gt2mjwgldlj.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2hxrgrkuz.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2lckgzqkl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2iwxbcbsf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gt2vzomplsf.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2qwehqwdn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gt2usehjuxy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gt2thnpyybn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2ufimpief.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjganihk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2awkngycn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2dtafayif.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2rbcxyfol.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gt2feddbesl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gt2hmbnqnjo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gt2kelolbrk.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gt2gyqiwbnt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gt2uletksjr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gt2qizpyecv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2qeuexdce.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2knrzgans.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2ocvoqkvg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gt2epwtfqgz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2jnuhayin.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gt2craakoow.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gt2fkyaffqx.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gt2bfigerud.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gt2adhvcujt.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2zkenpjuy.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gt2eiemlelj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gt2fhjxuubf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gt2qrnsgmuv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dspvzzgy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gt2otyrwxgi.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gt2zmnhzjvm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2ermnuuoj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gt2gcnyface.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gt2lzoplhwx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gt2zaowyzax.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcvgdcyi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2vmwsfflm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2wibiozrg.html


<!-- 参考信息 -->